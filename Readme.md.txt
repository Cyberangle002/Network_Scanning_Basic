# 🔍 Network Scanning & Vulnerability Assessment Project

This project demonstrates **basic network scanning and vulnerability assessment** performed on a vulnerable machine (Metasploitable2) using ethical hacking tools.  
The goal is to learn **how attackers scan networks** and how **defenders can secure systems** by identifying open ports and services.

---

## 🚀 Project Workflow
1. **Host Discovery**  
   - Tool: `netdiscover`  
   - Identified target machine IP in the local network.

2. **Ping Scan**  
   - Tool: `nmap -sn`  
   - Confirmed the host is live.

3. **Full Port Scanning**  
   - Tool: `nmap -p-`  
   - Enumerated all open ports on the target machine.

4. **Service & Version Detection**  
   - Tool: `nmap -sV`  
   - Gathered running service details (FTP, SSH, Apache, MySQL, etc.).

5. **OS Fingerprinting**  
   - Tool: `nmap -O`  
   - Detected target OS as Linux (2.6.x series).

6. **Web Vulnerability Scanning**  
   - Tool: `nikto`  
   - Identified misconfigurations and outdated services on the web server.

---

## 🛠 Tools Used
- **Netdiscover** → Host discovery  
- **Nmap** → Port, service, and OS scanning  
- **Nikto** → Web vulnerability scanning  

---

## 📸 Screenshots
All important outputs have been saved in the `Screenshots/` folder:

- `netdiscover.png` → Target machine IP found  
- `nmap_ping.png` → Host is up  
- `nmap_ports.png` → List of open ports  
- `nmap_services.png` → Services & versions  
- `nmap_os.png` → OS detection  
- `nikto_scan.png` → Web vulnerabilities  

---

## 📖 Learning Outcomes
- Understood the **importance of reconnaissance in cybersecurity**.  
- Learned to use **Nmap for port scanning, service detection, and OS fingerprinting**.  
- Gained hands-on experience in **web vulnerability detection**.  
- Practiced proper **documentation & evidence collection** for cybersecurity projects.  

---

## ⚠️ Disclaimer
This project is created **only for educational and ethical purposes**.  
All tests were performed on a **controlled lab environment (Metasploitable2)**.  
⚠️ Never scan networks or systems without proper authorization.
