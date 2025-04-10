# red-team-projects

# HTB Walkthroughs

This repository contains walkthroughs of several Hack The Box (HTB) machines. Each walkthrough includes reconnaissance, exploitation, and privilege escalation steps.

## Projects

### 1. UNDERPASS.HTB
- Initial nmap scan found ports 80 and 22.
- SNMP service running on port 161 provided useful information.
- Discovered daloRADIUS server and default credentials.
- Used SSH access and Mosh server to escalate privileges.
- Achieved root access.

[Read full walkthrough](./UNDERPASS.HTB.pdf)

### 2. LINKVORTEX.HTB
- Found ports 80 and 22 open.
- Identified a vulnerable Ghost CMS.
- Used directory brute force to discover hidden subdomains and git repositories.
- Exploited CVE-2023-40028 to retrieve sensitive files.
- Used SSH access and symlink attack to gain root privileges.

[Read full walkthrough](./LINKVORTEX.HTB.pdf)

### 3. DOG.HTB
- Discovered `.git` directory and extracted credentials using GitHack.
- Logged into the CMS using stolen credentials.
- Exploited a known CMS vulnerability for shell access.
- Used SSH access and privilege escalation techniques to gain root.

[Read full walkthrough](./DOG.HTB.pdf)

### 4. TITANIC.HTB
- Nmap scan found open ports and web services.
- Discovered a local file inclusion vulnerability.
- Extracted MySQL credentials and accessed the database.
- Cracked password hashes to gain SSH access.
- Retrieved root flag from the system.

[Read full walkthrough](./TITANIC.HTB.pdf)

### 5. ALERT.HTB
- Found an upload functionality allowing markdown files.
- Used a reverse shell payload to gain access.
- Decoded a password hash and used it for SSH login.
- Exploited an open-source monitoring tool to escalate privileges.
- Obtained root access.

[Read full walkthrough](./alert.htb.pdf)

---

## Usage
Clone the repository and read the walkthroughs to understand various penetration testing methodologies.
```bash
 git clone https://github.com/Gopalrajguru-tech/red-team-projects.git
 cd red-team-projects
```

## Connect with Me
[LinkedIn Profile](https://www.linkedin.com/in/gopal-rajguru2004/)

## Disclaimer
These walkthroughs are for educational purposes only. Do not attempt these techniques on unauthorized systems.

Happy Hacking! 🚀
