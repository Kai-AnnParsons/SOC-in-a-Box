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

## 🎯 Project Objectives
- Build a small virtual SOC using **free/open-source tools**
- Learn how logs, IDS, and SIEMs connect   
- Practice incident detection + response playbooks
- Develop foundational incident detection and response skills
- Present a working demo + report at the end  

---

## 🧑‍🤝‍🧑 Team Roles (Rotational Focus Areas)
Each team member contributes to all parts of the SOC lab.  
Roles are used as *focus areas* for organization and accountability and will rotate
throughout the project to ensure shared learning and hands-on experience.
- **Infrastructure & Networking**  pfSense firewall, Linux gateway VM, internal routing, Tailscale VPN access
- **SOC Platform & Detection**  Security Onion deployment, dashboards, log ingestion, alert triage
- **Endpoints & Telemetry**  Windows and Linux endpoints, Sysmon configuration, agent setup
- **Threat Intelligence & Detection Engineering**  Sigma rules, threat feeds, detection tuning and validation

- **Adversary Simulation (Red Team)**  Kali-based attack simulations (nmap, brute force, phishing, malware emulation)

- **Incident Response & Case Management**  Playbooks, case documentation, KPIs, reporting and post-incident review


---

## 🧰 Tools and Technologies
- **pfSense** → Firewall & DHCP  
- **Tailscale** → VPN Tunnel 
- **Security Onion** → SIEM, IDS (Suricata, Zeek), Fleet for agents  
- **Windows 10 Eval + Sysmon** → Endpoint telemetry  
- **Ubuntu** → Linux Gateway VM 
- **Kali Linux** → Attacker box (nmap, Hydra, GoPhish, EICAR)  
- **GitHub Issues** → Case tracking  
- **Google Docs/Slides** → Report + presentation  

---

## Skills Demonstrated
- SOC monitoring and alert triage
- add more skills here

---

## Future Enhancements
- Simulate Malware traffic
- Integrate threat intelligence 

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
