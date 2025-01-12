# Sub Saurus Rex

A dinosaur-themed **subdomain enumeration** and **vulnerability scanning** tool built in Python. Discover hidden subdomains, verify DNS records, check for missing security headers, and generate comprehensive reports—all wrapped in a fun T-Rex aesthetic.

![Sub Saurus Rex Logo](https://user-images.githubusercontent.com/placeholder-logo.png "Optional Logo")

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Example](#example)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)
8. [Disclaimer](#disclaimer)

---

## Features

- **Dino-Themed UI**  
  Engaging prompts and playful messages for an entertaining scanning experience.

- **Subdomain Enumeration**  
  - Supply a custom or default wordlist.  
  - Automatic DNS checks to confirm valid subdomains.

- **Vulnerability Checks**  
  - Basic security header inspection (e.g., HSTS, CSP, X-Frame-Options).  
  - Simple risk scoring based on missing or misconfigured headers.

- **Detailed Reports**  
  - Generate optional HTML, CSV, or PDF reports summarizing discovered subdomains and associated risks.

- **Optional Concurrency**  
  - Run scans faster using multiple threads or async I/O.

---

## Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/caselka/SubSaurasRex.git
   cd SubSaurasRex
   
**Disclaimer**
Ethical Use Only: Sub Saurus Rex is intended for educational or authorized security testing on domains you own or have explicit permission to test. The developer(s) assume no liability for misuse or damage caused by unauthorized use. Always follow legal and ethical guidelines when using cybersecurity tools.

**Happy Hunting with Sub Saurus Rex!**
Unleash the dino to uncover hidden subdomains and stamp out lurking vulnerabilities with a roar. For questions or feedback, feel free to open an issue or reach out on GitHub.
