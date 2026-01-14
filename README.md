# 🛡️ SOC-in-a-Box 

Welcome to our **SOC-in-a-Box** project! 🎉  
This repository documents the design, deployment, and operation of a home Security Operations Center (SOC) lab. This project allows us to implement our knowledge as cybersecurity students and emphasizes hands-on learning, real-world troubleshooting, and security best practices aligned with industry frameworks such as NIST CSF.

### This project is a **Work In Progress**: 
✅ Completed: Installed base VMs (pfSense, Linux Gateway, Windows endpoint, Security Onion), Configured Tailscale VPN, Configured Firewall and DHCP.

🟡 In progress: Security Onion configuration + manager/dashboard access. Windows endpoint Sysmon, agents. 

🔜 Next: add log sources (Windows endpoint), start alert triage workflow. 

### Team Members
We’re 6 teammates simulating attacks, detecting them, and responding like a real SOC team. 
- Kai-Ann Parsons
- Faith Aikhionbare
- Mahimaa Vardini Br
- Samarpita Sharma
- Riaa Sehgal
- Nada Elshami

---

## 🎯 Project Goals
- Build a small virtual SOC using **free/open-source tools** 
- Learn how logs, IDS, and SIEMs connect together  
- Practice incident detection + response playbooks  
- Present a working demo + report at the end  

---

## 🧑‍🤝‍🧑 Team Roles
- **R1 Infrastructure :** pfSense firewall, Linux Gateway VM, Tailscale VPN Tunnel
- **R2 SOC Platform :** Security Onion setup, dashboards  
- **R3 Endpoints :** Windows/Ubuntu VMs, Sysmon, agents  
- **R4 Threat Intel :** Sigma rules, intel feeds, tuning detections  
- **R5 Red Team :** Kali attacks (nmap, brute force, phishing, malware sim)  
- **R6 Case Mgmt :** Playbooks, case logs, KPIs, report  

---

## 🧰 Tools Used
- **pfSense** → Firewall & DHCP  
- **Tailscale** → VPN Tunnel 
- **Security Onion** → SIEM, IDS (Suricata, Zeek), Fleet for agents  
- **Windows 10 Eval + Sysmon** → Endpoint telemetry  
- **Ubuntu** → Linux Gateway VM 
- **Kali Linux** → Attacker box (nmap, Hydra, GoPhish, EICAR)  
- **GitHub Issues** → Case tracking  
- **Google Docs/Slides** → Report + presentation  

---

## 📂 Repo Structure
- /infra → network diagrams, firewall rules, Overview of setup
- /docs → guides, notes, configs
- /playbooks → incident response playbooks
- /rules → Sigma rules, Sysmon configs
- /evidence → screenshots, alerts, logs
- /redteam → attack scripts + results


---

## 📅 Timeline 
- **Stage 1** pfSense + Security Onion setup  
- **Stage 2** Endpoints, Sysmon, agent deployment  
- **Stage 3** Threat Intel feeds + rules  
- **Stage 4** Red Team test (nmap, EICAR, brute force)  
- **Stage 5** Blind drill + case tracking  
- **Stage 6** Final polish, report, demo  

---

## 📊 Deliverables
- ✅ Running SOC lab (SIEM, IDS, endpoints, attacker)  
- ✅ 3 incident playbooks (brute force, malware, phishing)  
- ✅ 2 dashboards (Analyst + Exec with MTTD/MTTR)  
- ✅ Final report (8–12 pages)  
- ✅ 8–10 min demo video  

---

✨ That’s it! This repo is our SOC adventure.  
