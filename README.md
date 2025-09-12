# 🛡️ SOC-in-a-Box 

Welcome to our **SOC-in-a-Box** project! 🎉  
This repo documents our journey as cybersecurity students building a **mini Security Operations Center (SOC)** at home.  
We’re 6 teammates simulating attacks, detecting them, and responding like a real SOC team.  

---

## 🎯 Project Goals
- Build a small virtual SOC using **free/open-source tools**  
- Learn how logs, IDS, and SIEMs connect together  
- Practice incident detection + response playbooks  
- Present a working demo + report at the end  

---

## 🧑‍🤝‍🧑 Team Roles
- **R1 Infrastructure :** pfSense firewall, VM network  
- **R2 SOC Platform :** Security Onion setup, dashboards  
- **R3 Endpoints ** Windows/Ubuntu VMs, Sysmon, agents  
- **R4 Threat Intel :** Sigma rules, intel feeds, tuning detections  
- **R5 Red Team :** Kali attacks (nmap, brute force, phishing, malware sim)  
- **R6 Case Mgmt :** Playbooks, case logs, KPIs, report  

---

## 🧰 Tools Used
- **pfSense** → Firewall & DHCP  
- **Security Onion** → SIEM, IDS (Suricata, Zeek), Fleet for agents  
- **Windows 10 Eval + Sysmon** → Endpoint telemetry  
- **Ubuntu** → Linux endpoint  
- **Kali Linux** → Attacker box (nmap, Hydra, GoPhish, EICAR)  
- **GitHub Issues** → Case tracking  
- **Google Docs/Slides** → Report + presentation  

---

## 📂 Repo Structure
/docs → guides, notes, configs
/playbooks → incident response playbooks
/rules → Sigma rules, Sysmon configs
/evidence → screenshots, alerts, logs
/redteam → attack scripts + results
/infra → network diagrams, firewall rules


---

## 🚀 How to Use
1. Clone this repo or download it as a zip.  
2. Follow setup instructions in `/docs/`.  
3. Review playbooks in `/playbooks/` to handle incidents.  
4. See `/evidence/` for screenshots of alerts and detections.  
5. Check GitHub Issues tab for case logs.  

---

## 📅 Timeline (Quick Build)
- **Day 1–2:** pfSense + Security Onion setup  
- **Day 3–4:** Endpoints, Sysmon, agent deployment  
- **Day 5:** Threat Intel feeds + rules  
- **Day 6:** Red Team test (nmap, EICAR, brute force)  
- **Day 7:** Blind drill + case tracking  
- **Day 8:** Final polish, report, demo  

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
