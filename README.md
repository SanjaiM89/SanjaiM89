  Sanjai M - GitHub README  \* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Courier New', monospace; } body { background: #0d1117; color: #c9d1d9; padding: 2rem; line-height: 1.6; max-width: 900px; margin: 0 auto; } .terminal { background: #0d1117; border-radius: 8px; padding: 2rem; box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5); border: 1px solid #30363d; } .terminal-header { display: flex; justify-content: space-between; align-items: center; padding: 0.5rem 1rem; background: #161b22; border-top-left-radius: 8px; border-top-right-radius: 8px; margin: -2rem -2rem 2rem -2rem; border-bottom: 1px solid #30363d; } .terminal-title { font-size: 1rem; font-weight: 500; } .terminal-controls { display: flex; } .control { width: 12px; height: 12px; border-radius: 50%; margin-left: 8px; } .close { background: #ff5f56; } .minimize { background: #ffbd2e; } .maximize { background: #27c93f; } .prompt { color: #58a6ff; margin-right: 8px; } .command { margin-bottom: 1.5rem; display: flex; align-items: flex-start; } .command-input { color: #f0f6fc; background: transparent; border: none; outline: none; width: 100%; font-family: 'Courier New', monospace; font-size: 1rem; } .command-output { margin: 0.5rem 0 1.5rem 2rem; padding-left: 1rem; border-left: 2px solid #58a6ff; } .highlight { color: #58a6ff; font-weight: bold; } .accent { color: #ff7b72; } .success { color: #3fb950; } .warning { color: #d29922; } .info { color: #a5d6ff; } .section-title { font-size: 1.2rem; margin: 2rem 0 1rem; border-bottom: 1px solid #30363d; padding-bottom: 0.5rem; color: #58a6ff; } .skills-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(120px, 1fr)); gap: 1rem; margin: 1rem 0; } .skill-item { background: #161b22; padding: 0.5rem; border-radius: 4px; text-align: center; border: 1px solid #30363d; transition: transform 0.2s; } .skill-item:hover { transform: translateY(-3px); border-color: #58a6ff; } .social-links { display: flex; gap: 1rem; margin: 1rem 0; } .social-link { color: #c9d1d9; text-decoration: none; padding: 0.5rem 1rem; border: 1px solid #30363d; border-radius: 4px; transition: all 0.2s; display: flex; align-items: center; gap: 0.5rem; } .social-link:hover { background: #58a6ff; color: #0d1117; } .blink { animation: blink 1s infinite; } @keyframes blink { 0%, 50% { opacity: 1; } 51%, 100% { opacity: 0; } } @media (max-width: 768px) { body { padding: 1rem; } .terminal { padding: 1rem; } .skills-grid { grid-template-columns: repeat(auto-fill, minmax(100px, 1fr)); } .social-links { flex-direction: column; } }

sanjaim89@github:~

sanjaim89@github:~$ cat about\_me.txt

Hello! I'm Sanjai M, a passionate developer with interest in various technologies.

🔭 I’m currently working on Online compilers

🌱 I’m currently learning Machine Learning

👯 I’m looking to collaborate on Linux Kernel development

📫 How to reach me: sanjai@myyahoo.com

sanjaim89@github:~$ ls projects/

FitXP - A fitness application

sanjaim89@github:~$ connect --social

Connect with me:

[GitHub](https://github.com/SanjaiM89) [LinkedIn](https://linkedin.com/in/sanjaim89)

sanjaim89@github:~$ show skills

Languages and Tools:

C++

PythonFastAPI

Docker

Linux

MySQL

React

Rust

sanjaim89@github:~$ \_

// Simple typewriter effect for the last command line document.addEventListener('DOMContentLoaded', function() { const blinkElement = document.querySelector('.blink'); setInterval(() => { blinkElement.style.opacity = blinkElement.style.opacity === '0' ? '1' : '0'; }, 500); });
