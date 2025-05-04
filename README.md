<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neon Ethical Hacker GitHub Banner</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@400;700&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Ubuntu+Mono:wght@400;700&display=swap');
        
        body {
            margin: 0;
            padding: 0;
            background-color: #0a0a0a;
            color: #00ff41;
            font-family: 'Source Code Pro', monospace;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            background-color: #0a0a0a;
            background-image: 
                radial-gradient(#00ff4133 1px, transparent 1px),
                radial-gradient(#00ff4122 1px, transparent 1px);
            background-size: 30px 30px, 15px 15px;
            background-position: 0 0, 15px 15px;
            border: 1px solid #00ff41;
            padding: 20px;
            box-shadow: 0 0 20px #00ff4155, inset 0 0 10px #00ff4155;
            position: relative;
            overflow: hidden;
        }
        
        .container::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, transparent, #00ff41, transparent);
            animation: scanline 4s linear infinite;
        }
        
        @keyframes scanline {
            0% { top: 0; }
            100% { top: 100%; }
        }
        
        .header {
            text-align: center;
            margin-bottom: 20px;
            position: relative;
        }
        
        .terminal {
            font-family: 'Ubuntu Mono', monospace;
            font-size: 2.2em;
            font-weight: bold;
            color: #00ff41;
            margin: 10px 0;
            text-shadow: 0 0 10px #00ff4188;
            letter-spacing: 1px;
            animation: pulse 4s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { text-shadow: 0 0 10px #00ff4188; }
            50% { text-shadow: 0 0 20px #00ff41cc; }
        }
        
        .blink::after {
            content: "█";
            animation: blink 1s infinite;
        }
        
        @keyframes blink {
            0%, 49% { opacity: 1; }
            50%, 100% { opacity: 0; }
        }
        
        h2 {
            position: relative;
            display: inline-block;
            color: #f0f0f0;
            margin: 15px 0;
            font-size: 1.5em;
            padding: 5px 15px;
            background-color: #111;
            box-shadow: 0 0 10px #00ff4155;
            border-left: 3px solid #00ff41;
        }
        
        .description {
            text-align: center;
            font-size: 1.1em;
            margin: 15px auto;
            max-width: 800px;
            line-height: 1.5;
            background-color: rgba(0, 10, 2, 0.6);
            padding: 10px;
            border-radius: 5px;
        }
        
        .skills {
            text-align: center;
            margin: 20px 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill {
            background-color: #111;
            color: #00ff41;
            padding: 5px 12px;
            border-radius: 4px;
            font-weight: bold;
            border: 1px solid #00ff4155;
            box-shadow: 0 0 8px #00ff4133;
            transition: all 0.3s ease;
        }
        
        .skill:hover {
            transform: translateY(-3px);
            box-shadow: 0 0 15px #00ff4188;
        }
        
        .section {
            margin: 25px 0;
            position: relative;
        }
        
        .projects {
            list-style-type: none;
            padding: 0;
            margin: 0 auto;
            max-width: 800px;
        }
        
        .project-item {
            margin: 15px 0;
            padding: 10px 15px;
            background-color: rgba(0, 20, 5, 0.3);
            border-left: 3px solid #00ff41;
            position: relative;
            transition: transform 0.3s ease;
        }
        
        .project-item:hover {
            transform: translateX(5px);
            background-color: rgba(0, 30, 10, 0.5);
        }
        
        .project-item::before {
            content: ">";
            color: #00ff41;
            position: absolute;
            left: -15px;
            top: 10px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .project-item:hover::before {
            opacity: 1;
        }
        
        .project-title {
            font-weight: bold;
            color: #00ff41;
        }
        
        .loading-bar {
            text-align: center;
            margin: 30px 0;
        }
        
        .connect {
            text-align: center;
            margin-top: 30px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 15px;
        }
        
        .social-link {
            color: #00ff41;
            text-decoration: none;
            padding: 8px 15px;
            border: 1px solid #00ff41;
            border-radius: 4px;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .social-link::before {
            content: "";
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, #00ff4133, transparent);
            transition: left 0.7s ease;
        }
        
        .social-link:hover {
            box-shadow: 0 0 15px #00ff4188;
            background-color: rgba(0, 255, 65, 0.1);
        }
        
        .social-link:hover::before {
            left: 100%;
        }
        
        .ascii-art {
            text-align: center;
            font-family: monospace;
            font-size: 0.7em;
            line-height: 1.2;
            color: #00ff41;
            white-space: pre;
            margin: 20px auto;
            max-width: 300px;
            opacity: 0.8;
        }
        
        .binary-decoration {
            position: absolute;
            font-size: 0.8em;
            color: #00ff4133;
            pointer-events: none;
            user-select: none;
        }
        
        #binary1 {
            top: 20px;
            left: 20px;
        }
        
        #binary2 {
            bottom: 20px;
            right: 20px;
        }
        
        .glitch-effect {
            position: relative;
        }
        
        .glitch-effect::before {
            content: attr(data-text);
            position: absolute;
            left: -2px;
            text-shadow: -1px 0 red;
            top: 0;
            color: #00ff41;
            overflow: hidden;
            clip: rect(0, 900px, 0, 0);
            animation: glitch-effect 2s infinite linear alternate-reverse;
        }
        
        .glitch-effect::after {
            content: attr(data-text);
            position: absolute;
            left: 2px;
            text-shadow: -1px 0 blue;
            top: 0;
            color: #00ff41;
            overflow: hidden;
            clip: rect(0, 900px, 0, 0);
            animation: glitch-effect 3s infinite linear alternate-reverse;
        }
        
        @keyframes glitch-effect {
            0% {
                clip: rect(31px, 9999px, 94px, 0);
            }
            10% {
                clip: rect(112px, 9999px, 76px, 0);
            }
            20% {
                clip: rect(85px, 9999px, 77px, 0);
            }
            30% {
                clip: rect(149px, 9999px, 34px, 0);
            }
            40% {
                clip: rect(38px, 9999px, 92px, 0);
            }
            50% {
                clip: rect(102px, 9999px, 5px, 0);
            }
            60% {
                clip: rect(51px, 9999px, 12px, 0);
            }
            70% {
                clip: rect(2px, 9999px, 3px, 0);
            }
            80% {
                clip: rect(30px, 9999px, 29px, 0);
            }
            90% {
                clip: rect(76px, 9999px, 85px, 0);
            }
            100% {
                clip: rect(25px, 9999px, 11px, 0);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="binary-decoration" id="binary1">01001110 01100101 01110110 01100101 01110010<br>01010011 01110100 01101111 01110000<br>01001100 01100101 01100001 01110010 01101110 01101001 01101110 01100111</div>
        
        <div class="header">
            <div class="terminal glitch-effect" data-text="ma1loc@github:~$ _">ma1loc@github:~$ <span class="blink"></span></div>
            <h2>whoami?</h2>
        </div>
        
        <div class="description">
            1337 student based in Morocco, exploring the depths of cyberspace.<br>
            Passionate about ethical hacking, reverse engineering broken systems,<br>
            and crafting custom security tools to uncover the hidden.
        </div>
        
        <div class="skills">
            <div class="skill">C</div>
            <div class="skill">Python</div>
            <div class="skill">Bash</div>
            <div class="skill">Git</div>
            <div class="skill">Linux</div>
            <div class="skill">Networking</div>
            <div class="skill">Pentesting</div>
        </div>
        
        <div class="section">
            <h2>featured work</h2>
            <ul class="projects">
                <li class="project-item">
                    <span class="project-title">mac_addr_changer</span> — A surgical tool to modify device MAC addresses for enhanced privacy.
                </li>
                <li class="project-item">
                    <span class="project-title">network_scanner</span> — Intelligence gathering tool that reveals network devices and potential entry points.
                </li>
            </ul>
        </div>
        
        <div class="section">
            <h2>currently working on</h2>
            <ul class="projects">
                <li class="project-item">
                    ⚡ Mastering Python to architect sophisticated ethical hacking tools from scratch
                </li>
            </ul>
        </div>
        
        <div class="loading-bar">
            <img src="https://readme-typing-svg.demolab.com?font=Ubuntu+Mono&pause=500&color=00FF41&center=true&vCenter=true&width=500&lines=Knowledge+is+loading...;System+breach+imminent...;Scanning+vulnerabilities...;Ethical+hacker+mode+activated..." alt="Typing SVG" />
        </div>
        
        <div class="ascii-art">
  /\\\\\\\\\\\\\\    /\\\\\\\\\\\\   
 /\\\//////////\\\ /\\\////////\\\ 
 /\\\/       \///  /\\\/       \//\\
 /\\\             /\\\         \///
 /\\\              \/\\\         \/
 /\\\              \//\\\         \
 /\\\               \///\\\        \
 /\\\\\\\\\\\\\\\\   \////\\\\\\\\\\
 \///////////////     \///////////
        </div>
        
        <div class="connect">
            <h2>let's connect</h2>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/youness-anflous-80b750257/" target="_blank" class="social-link">LinkedIn</a>
                <a href="https://x.com/YounessAnflous" target="_blank" class="social-link">Twitter</a>
            </div>
        </div>
        
        <div class="binary-decoration" id="binary2">01000101 01110100 01101000 01101001 01100011 01100001 01101100<br>01001000 01100001 01100011 01101011 01100101 01110010<br>01001101 01100001 00110001 01101100 01101111 01100011</div>
    </div>
</body>
</html>
