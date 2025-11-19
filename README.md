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
oSaint is an OSINT tool that can do Passive and Active OSINT. It can be installed on UNIX systems. (eg. Linux, BSD, MacOS, etc.) 

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
git clone https://github.com/jamaal-hussein/osaint/
cd osaint
sudo chmod +x oSaint
sudo mv oSaint /usr/bin/
```

# Usage
```
oSaint -p "subject"          : Passive Recon (Web summary + DDG)
oSaint -a target.com          : Standard Active Recon
oSaint -aS target.com         : Safe Mode (NO brute-force, NO nmap)
oSaint -aR target.com         : Risky Mode (Full brute-force + nmap + whatweb)
oSaint --help                 : Show the help menu
```
