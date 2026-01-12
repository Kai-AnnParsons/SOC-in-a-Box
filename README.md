# 🛡️ SOC-in-a-Box 

Welcome to our **SOC-in-a-Box** project! 🎉  
This repo documents our journey as cybersecurity students building a **mini Security Operations Center (SOC)** at home to learn basic cybersecurity concepts. 
We’re 6 teammates simulating attacks, detecting them, and responding like a real SOC team. 

### This project is a **Work In Progress**: 
✅ Completed: Installed base VMs (pfSense, Linux Gateway, Windows endpoint, Security Onion), Configured Tailscale VPN, Conifgured Firewall and DHCP.

🟡 In progress: Security Onion configuration + manager/dashboard access. Windows endpoint Sysmon, agents. 

🔜 Next: add log sources (Windows endpoint), start alert triage workflow. 

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
- /docs → guides, notes, configs
- /playbooks → incident response playbooks
- /rules → Sigma rules, Sysmon configs
- /evidence → screenshots, alerts, logs
- /redteam → attack scripts + results
- /infra → network diagrams, firewall rules

---

## 📅 Timeline 
- **Week 1** pfSense + Security Onion setup  
- **Week 2** Endpoints, Sysmon, agent deployment  
- **Week 3** Threat Intel feeds + rules  
- **Week 4** Red Team test (nmap, EICAR, brute force)  
- **Week 5** Blind drill + case tracking  
- **Week 6** Final polish, report, demo  

---

## 📊 Deliverables
- ✅ Running SOC lab (SIEM, IDS, endpoints, attacker)  
- ✅ 3 incident playbooks (brute force, malware, phishing)  
- ✅ 2 dashboards (Analyst + Exec with MTTD/MTTR)  
- ✅ Final report (8–12 pages)  
- ✅ 8–10 min demo video  

---

## ⚠️ Safety Note
- Lab is **isolated** (NAT network, no external attacks).  
- Red team runs only against **our own VMs**.  
- Always snapshot before simulating attacks. 

---

✨ That’s it! This repo is our SOC adventure.  
