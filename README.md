<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanjai M - GitHub README</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Courier New', monospace;
        }
        
        body {
            background: #0d1117;
            color: #c9d1d9;
            padding: 2rem;
            line-height: 1.6;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .terminal {
            background: #0d1117;
            border-radius: 8px;
            padding: 2rem;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            border: 1px solid #30363d;
        }
        
        .terminal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0.5rem 1rem;
            background: #161b22;
            border-top-left-radius: 8px;
            border-top-right-radius: 8px;
            margin: -2rem -2rem 2rem -2rem;
            border-bottom: 1px solid #30363d;
        }
        
        .terminal-title {
            font-size: 1rem;
            font-weight: 500;
        }
        
        .terminal-controls {
            display: flex;
        }
        
        .control {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            margin-left: 8px;
        }
        
        .close {
            background: #ff5f56;
        }
        
        .minimize {
            background: #ffbd2e;
        }
        
        .maximize {
            background: #27c93f;
        }
        
        .prompt {
            color: #58a6ff;
            margin-right: 8px;
        }
        
        .command {
            margin-bottom: 1.5rem;
            display: flex;
            align-items: flex-start;
        }
        
        .command-input {
            color: #f0f6fc;
            background: transparent;
            border: none;
            outline: none;
            width: 100%;
            font-family: 'Courier New', monospace;
            font-size: 1rem;
        }
        
        .command-output {
            margin: 0.5rem 0 1.5rem 2rem;
            padding-left: 1rem;
            border-left: 2px solid #58a6ff;
        }
        
        .highlight {
            color: #58a6ff;
            font-weight: bold;
        }
        
        .accent {
            color: #ff7b72;
        }
        
        .success {
            color: #3fb950;
        }
        
        .warning {
            color: #d29922;
        }
        
        .info {
            color: #a5d6ff;
        }
        
        .section-title {
            font-size: 1.2rem;
            margin: 2rem 0 1rem;
            border-bottom: 1px solid #30363d;
            padding-bottom: 0.5rem;
            color: #58a6ff;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            gap: 1rem;
            margin: 1rem 0;
        }
        
        .skill-item {
            background: #161b22;
            padding: 0.5rem;
            border-radius: 4px;
            text-align: center;
            border: 1px solid #30363d;
            transition: transform 0.2s;
        }
        
        .skill-item:hover {
            transform: translateY(-3px);
            border-color: #58a6ff;
        }
        
        .social-links {
            display: flex;
            gap: 1rem;
            margin: 1rem 0;
        }
        
        .social-link {
            color: #c9d1d9;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border: 1px solid #30363d;
            border-radius: 4px;
            transition: all 0.2s;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .social-link:hover {
            background: #58a6ff;
            color: #0d1117;
        }
        
        .blink {
            animation: blink 1s infinite;
        }
        
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0; }
        }
        
        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            .terminal {
                padding: 1rem;
            }
            
            .skills-grid {
                grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            }
            
            .social-links {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="terminal">
        <div class="terminal-header">
            <div class="terminal-title">sanjaim89@github:~</div>
            <div class="terminal-controls">
                <div class="control close"></div>
                <div class="control minimize"></div>
                <div class="control maximize"></div>
            </div>
        </div>
        
        <div class="command">
            <span class="prompt">sanjaim89@github:~$</span>
            <span class="command-input">cat about_me.txt</span>
        </div>
        
        <div class="command-output">
            <p>Hello! I'm <span class="highlight">Sanjai M</span>, a passionate developer with interest in various technologies.</p>
            <p>🔭 I’m currently working on <span class="accent">Online compilers</span></p>
            <p>🌱 I’m currently learning <span class="success">Machine Learning</span></p>
            <p>👯 I’m looking to collaborate on <span class="warning">Linux Kernel</span> development</p>
            <p>📫 How to reach me: <span class="info">sanjai@myyahoo.com</span></p>
        </div>
        
        <div class="command">
            <span class="prompt">sanjaim89@github:~$</span>
            <span class="command-input">ls projects/</span>
        </div>
        
        <div class="command-output">
            <p><span class="highlight">FitXP</span> - A fitness application</p>
        </div>
        
        <div class="command">
            <span class="prompt">sanjaim89@github:~$</span>
            <span class="command-input">connect --social</span>
        </div>
        
        <div class="command-output">
            <p>Connect with me:</p>
            <div class="social-links">
                <a href="https://github.com/SanjaiM89" class="social-link">
                    <i class="fab fa-github"></i> GitHub
                </a>
                <a href="https://linkedin.com/in/sanjaim89" class="social-link">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
            </div>
        </div>
        
        <div class="command">
            <span class="prompt">sanjaim89@github:~$</span>
            <span class="command-input">show skills</span>
        </div>
        
        <div class="command-output">
            <p>Languages and Tools:</p>
            <div class="skills-grid">
                <div class="skill-item">C++</div>
                <div class="skill-item">PythonFastAPI</div>
                <div class="skill-item">Docker</div>
                <div class="skill-item">Linux</div>
                <div class="skill-item">MySQL</div>
                <div class="skill-item">React</div>
                <div class="skill-item">Rust</div>
            </div>
        </div>
        
        <div class="command">
            <span class="prompt">sanjaim89@github:~$</span>
            <span class="command-input"><span class="blink">_</span></span>
        </div>
    </div>

    <script>
        // Simple typewriter effect for the last command line
        document.addEventListener('DOMContentLoaded', function() {
            const blinkElement = document.querySelector('.blink');
            setInterval(() => {
                blinkElement.style.opacity = blinkElement.style.opacity === '0' ? '1' : '0';
            }, 500);
        });
    </script>
</body>
</html>
