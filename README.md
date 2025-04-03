<h1 align="center">Zer0's Cybersecurity Terminal</h1>
---
```html
<script>
// Store command history
let history = [];
function handleCommand() {
    let input = document.getElementById("terminalInput").value.toLowerCase();
    let output = document.getElementById("terminalOutput");
    history.push(input);
    localStorage.setItem("terminalHistory", JSON.stringify(history));
    
    switch(input) {
        case "whoami":
            output.innerHTML = "Zer0 - Cybersecurity Enthusiast | Penetration Tester | Researcher | Hackathon Winner";
            break;
        case "ls -l ~/projects":
            output.innerHTML = "AssureFi/  Medica/  Compliance_Automation_Tool/  Network_Analyzer/";
            break;
        case "cat ~/achievements.txt":
            output.innerHTML = "- National & International Hackathon Victories 🥇<br>- World Record Holder - Medica (Augmented Reality) 🌎<br>- Top 20 in Technovate for India Initiative 🚀<br>- Daily TryHackMe Streak | HTB Solver 🔥<br>- Developed cutting-edge security tools and compliance automation frameworks 🎯";
            break;
        case "man zer0":
            output.innerHTML = "Zer0: A cybersecurity specialist dedicated to ethical hacking, AI security, and compliance automation.";
            break;
        case "ls -l ~/certifications":
            output.innerHTML = "OSCP/  CEH/  CompTIA Security+/  TryHackMe Top 1%/";
            break;
        case "nmap -A zer0":
            output.innerHTML = "Scanning skills... Open ports: 80 (Web Security), 443 (Cryptography), 22 (Penetration Testing), 8080 (AI Security)";
            break;
        default:
            output.innerHTML = "Command not found. Try: whoami, ls -l ~/projects, cat ~/achievements.txt, man zer0, ls -l ~/certifications, nmap -A zer0";
    }
}
</script>

<style>
  .terminal {
    background: black;
    color: limegreen;
    padding: 10px;
    font-family: monospace;
  }
  #terminalInput {
    background: black;
    color: limegreen;
    border: none;
    outline: none;
  }
  @keyframes blink {
    50% { opacity: 0; }
  }
  .cursor { animation: blink 1s step-end infinite; }
</style>

<div class="terminal">
    <span style="color:white;">visitor@zer0:~$</span> 
    <input type="text" id="terminalInput" onkeypress="if(event.key === 'Enter') handleCommand();" autofocus>
    <span class="cursor">|</span>
    <br>
    <p id="terminalOutput"></p>
</div>
```
👨‍💻 About Me

🔹 Penetration Tester | Researcher | Hackathon Winner
🔹 Cybersecurity Enthusiast | Compliance Expert
🔹 Building Agentic AI, Augmented Reality & Compliance Automation

I’m a cybersecurity professional with a passion for ethical hacking, automation, and AI-driven security solutions. I love competing in hackathons, breaking security barriers, and solving real-world problems with technology.


---

🏆 Achievements

🥇 National & International Hackathon Victories

🌎 World Record Holder - Medica (Augmented Reality)

🚀 Top 20 in Technovate for India Initiative

🔥 Daily TryHackMe Streak | HTB Solver

🎯 Developed cutting-edge security tools and compliance automation frameworks



---

🔧 Technical Skills

Languages: C++, Python, Bash

Tools & Frameworks: Nmap, Burp Suite, Metasploit

Security Domains: Web & Network Penetration Testing, Threat Hunting, Compliance Auditing



---

📌 Featured Projects

🛡️ AssureFi (Agentic AI for Cybersecurity)

🏥 Medica (Augmented Reality in Healthcare)

📜 Compliance Automation Tool (Ensuring Regulatory Compliance)

🌐 Network Analyzer (Real-time Traffic Monitoring)



---

📈 My Stats

GitHub Activity



TryHackMe Progress



Latest Medium Articles

<!-- Medium Auto-Update Widget -->
---

📡 Let's Connect!

🏴‍☠️ TryHackMe

📜 Medium Articles

🐙 GitHub

📧 zer0@cybersecurity.dev


# Thank you for visiting! Keep hacking ethically.

