
cat << 'EOF' > README.md
<h1 align="center">
  <a href="#"><img src=".imgs/photo_2025-05-28_16-53-09.jpg" alt="TX0 Bot" width="200"></a>
  <br>
  <b>TX0 Bot</b>
</h1>

<p align="center">
  A Modern, Modular Social Engineering Toolkit for Web-Based Recon and Exploitation
</p>

<p align="center">
  <a href="https://python.org"><img src="https://img.shields.io/badge/python-v3-blue"></a>
  <a href="https://php.net"><img src="https://img.shields.io/badge/php-7.4.4-green"></a>
  <a href="https://en.wikipedia.org/wiki/Linux"><img src="https://img.shields.io/badge/platform-Linux-red"></a>
</p>

---

##  Introduction

**TX0 Bot** is a professional-grade social engineering framework built for penetration testers, ethical hackers, and security researchers.  
It provides an advanced web-based control panel for gathering device information, geolocation, webcam access, and microphone access by leveraging phishing-based attack templates.

TX0 Bot was designed with flexibility in mind — allowing users to customize payload templates, control log data, and optionally forward collected information via Telegram bots or webhooks.  
The tool works seamlessly on localhost or your personal server/hosting, with optional tunnel management via Ngrok or any tunneling service of your choice.

This project is intended for **educational use, penetration testing in controlled environments, and security awareness demonstrations only**.

---

##  Features Overview

A detailed breakdown of the core features included in TX0 Bot:

- **Device Information Collection:**  
  Harvest detailed information from the victim’s browser and device without needing explicit permissions.

- **Geolocation Tracking:**  
  Attempt to obtain precise geolocation from mobile devices (using browser-based APIs where possible).

- **Webcam Access:**  
  Capture images or video stream requests via the victim’s webcam (with browser prompt).

- **Microphone Access:**  
  Similar to webcam functionality, access the microphone through crafted web templates.

- **Customizable Templates:**  
  Use and modify phishing pages tailored for different social engineering scenarios (chat apps, fake offers, services, etc.).

- **Telegram Integration:**  
  Send captured information and logs directly to a specified Telegram bot/channel.

- **Webhook Support:**  
  Forward events, logs, and captured data to your custom endpoint via HTTP POST requests.

- **Downloadable and Clearable Logs:**  
  Download stored logs or purge them directly from the control panel.

- **Runs on Localhost or Hosting:**  
  Deploy the framework on your local machine for testing or upload it to your personal hosting for real-world scenarios.

- **Ngrok (Deprecated):**  
  Auto Ngrok integration has been removed in the latest version — tunneling is now managed manually for better control.

---

##  What’s New — Latest Update (July 8, 2025)

- Full codebase restructured for improved performance and modularity.
- Transitioned from a CLI tool to a web-based GUI with modern UI.
- Ngrok auto-start removed to avoid detection issues and restrictions — users manage their tunnels manually.
- Log management improved (download and clear logs directly from web panel).
- Telegram bot integration enhanced.
- Webhook event forwarding option added.
- Bugfixes from older releases fully addressed.
- Template system optimized for faster loading and easier customization.

---

##  Installation & Dependencies

### System Requirements:

- Linux-based OS (Kali, Parrot, Ubuntu, or WSL recommended)
- Python 3.x
- PHP 7.x+
- Git
- Ngrok (if using tunneling)

---

### Install Dependencies:

\`\`\`bash
sudo apt update
sudo apt install php python3 git
\`\`\`

Download Ngrok if needed: [https://ngrok.com/download](https://ngrok.com/download)

---

##  Usage Guide

Once dependencies are in place, clone the repository:

\`\`\`bash
git clone https://github.com/yourrepo/TX0-Bot.git
cd TX0-Bot
python3 TX0-BotV2.py -h
\`\`\`

### Command-Line Options:

| Option                  | Description                                       |
|:------------------------|:--------------------------------------------------|
| \`-h, --help\`             | Show help message and exit                        |
| \`-k KML, --kml KML\`      | Specify a KML file for geolocation display        |
| \`-p PORT, --port PORT\`   | Set custom server port (default is 8080)          |
| \`-u, --update\`           | Check for latest updates                          |
| \`-v, --version\`          | Display current version number                    |
| \`-t TEMPLATE\`            | Select a template by index                        |
| \`-d, --debugHTTP\`        | Disable HTTPS redirect for debug purposes         |
| \`--telegram token:chatId\`| Send logs to Telegram bot                         |
| \`--webhook WEBHOOK\`      | Forward logs and events to a webhook URL          |

---

## 🔧 Environment Variables (for Auto Deployment)

You can configure key parameters via environment variables to automate setup:

- \`DEBUG_HTTP\` — Disable redirect
- \`PORT\` — Web server port
- \`TEMPLATE\` — Template index
- \`TITLE\` — Web page or group title
- \`REDIRECT\` — Redirect URL post execution
- \`IMAGE\` — Image for the web page
- \`DESC\` — Description for the template
- \`SITENAME\` — Name of the fake website
- \`DISPLAY_URL\` — URL displayed on template
- \`MEM_NUM\` — Group member count (if applicable)
- \`ONLINE_NUM\` — Online member count
- \`TELEGRAM\` — Telegram token and chat ID
- \`WEBHOOK\` — Webhook URL to receive POST requests

---

##  Default Access Credentials

Upon initial setup, access the web panel using:

| Username | Password |
|:------------|:------------|
| \`admin\`   | \`admin\`    |

It’s highly recommended to update these immediately after deployment.

---

##  Important Notes

- This tool is designed for use in **legal penetration testing, educational, and research environments only.**
- Never deploy this tool on third-party infrastructures without clear, written permission.
- Always respect privacy, data protection, and local laws.
- Ngrok integration has been deprecated to avoid restrictions and user distrust of public tunnels. Personal hosting is recommended for serious operations.

---

##  Legal Disclaimer

This software is developed for ethical hacking, security research, and educational use.  
The developer is not responsible for any misuse or damage caused by this tool.

Unauthorized spying, data collection, or unauthorized system access is illegal and punishable by law in most countries.

You are solely responsible for your actions.

---

##  Developer & Contact

Developed by **[TX05730](https://github.com/TX05730)**

- [Official Telegram Channel](https://t.me/+JFIQ4ln2Cug3ZTdi)
- [Demo Video](https://odysee.com/@thewhiteh4t:2/seeker_v126_demo:e)

For collaborations, permissions, or questions — contact via Telegram.

---

##  Final Remarks

TX0 Bot was built to help security specialists better understand modern social engineering techniques, and to create awareness on how attackers exploit browser permissions and social habits.  
It serves as both a **learning platform and demonstration toolkit** for live security workshops and penetration tests.

Contributions are welcome — submit pull requests or issues via the GitHub repo.

---
EOF
