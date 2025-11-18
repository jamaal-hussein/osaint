```
      (                           
      )\ )                     )  
     (()/(    )  (          ( /(  
  (   /(_))( /(  )\   (     )\()) 
  )\ (_))  )(_))((_)  )\ ) (_))/  
 ((_)/ __|((_)_  (_) _(_/( | |_   
/ _ \\__ \/ _` | | || ' \))|  _|  
\___/|___/\__,_| |_||_||_|  \__|  
```
oSaint is an open-source OSINT tool that performs both Passive and Active reconnaissance.
It runs on all UNIX-like systems (Linux, BSD, macOS, etc) because all 
required tools are automatically installed via git clone, wget, or source builds.

# Features
• WHOIS Lookup  
• DNS Enumeration  
• Subdomain Brute Forcing  
• HTTP Fingerprinting (WhatWeb)  
• Aggressive Nmap Scan  
• Auto-installs missing tools (universal, no apt, no pacman needed)
• 100% portable script — works on ANY distro

# Installation
```
git clone https://github.com/jamaal-hussein/osaint/oSaint
cd oSaint
sudo chmod +x oSaint
sudo mv oSaint /usr/bin/
```

# Usage
oSaint -p "subject"          : Passive Recon (Web summary + DDG)
oSaint -a target.com          : Standard Active Recon
oSaint -aS target.com         : Safe Mode (NO brute-force, NO nmap)
oSaint -aR target.com         : Risky Mode (Full brute-force + nmap + whatweb)
oSaint --help                 : Show the help menu
