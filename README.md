
# Raspberry Pi Mini SOC

A low-cost distributed security monitoring lab built on Raspberry Pi infrastructure, featuring a modular Python-based authentication log analysis engine to detect suspicious login activity and simulate real-world Security Operations Center (SOC) workflows.

---

## 📌 Project Overview

This project is a multi-phase cybersecurity lab designed to evolve from a Python-based log analysis tool into a distributed Raspberry Pi–powered security monitoring system.

The system simulates core SOC functions:
- Log collection  
- Authentication monitoring  
- Threat detection  
- Security reporting  

The goal is to create a practical, low-cost platform for learning, experimentation, and research in cybersecurity and distributed systems.

---

## 🎯 Objectives

- Develop a Python-based log analysis engine for authentication logs  
- Detect suspicious login behavior (e.g., repeated failed attempts)  
- Build a distributed Raspberry Pi monitoring environment  
- Simulate real-world SOC workflows  
- Support future research on detection accuracy and system performance  

---

## 🧠 Key Features (Planned & In Progress)

- 🔍 Authentication log parsing (`/var/log/auth.log`)  
- 🚨 Detection of repeated failed login attempts  
- 🌐 Identification of suspicious IP addresses  
- ⚙️ Configurable detection thresholds  
- 📊 Structured report generation (JSON, CSV, TXT)  
- ⏱️ Scheduled automated analysis  
- 🖥️ Centralized log collection (multi-node)  
- 📈 Dashboard for visualization (planned)  
- 🔔 Alerting system for suspicious activity (planned)  

---

## 🏗️ System Architecture (Planned)

### Node Roles (Future Cluster Design)

- **Log Sources** – Devices generating authentication logs  
- **Log Collector** – Central node responsible for storing logs  
- **Analysis Engine** – Python-based system for parsing and detection  
- **Dashboard Node** – Visualization and monitoring interface  
- **Attack Simulator** – Controlled environment for generating test activity  

---

## 🔁 System Workflow (Planned)

1. Log sources generate authentication data  
2. Logs are collected or forwarded to a central node  
3. The analysis engine processes incoming logs  
4. Suspicious behavior is identified using configurable thresholds  
5. Reports and alerts are generated  
6. Results are stored and/or visualized  

---

## 🧰 Technologies Used

- Python  
- Linux (Raspberry Pi OS / Ubuntu)  
- Raspberry Pi cluster (planned)  
- SSH / authentication logs  
- Git & GitHub  

---

## 📂 Repository Structure

```
raspberry-pi-mini-soc/
├── README.md
├── docs/
│   ├── architecture.md
│   ├── research-plan.md
│   └── build-phases.md
├── hardware/
│   ├── materials-list.md
│   └── cluster-layout.md
├── software/
│   └── analysis-engine/
├── diagrams/
└── roadmap.md
```


---

## 🛠️ Current Focus (Phase 1)

- Build core Python log analysis engine  
- Parse authentication logs  
- Detect suspicious login patterns  
- Generate structured reports  

---

## 🗺️ Project Roadmap

- [ ] Phase 1: Python log analysis engine (current)  
- [ ] Phase 2: Modularization and configuration system  
- [ ] Phase 3: Deployment on Raspberry Pi  
- [ ] Phase 4: Centralized log collection (multi-node)  
- [ ] Phase 5: Dashboard and visualization  
- [ ] Phase 6: Alerting system  
- [ ] Phase 7: Research and performance evaluation  

---

## 🔬 Future Research Direction

This project will be extended into a senior research project focused on:

- Evaluating detection accuracy of authentication-based threat models  
- Measuring performance on low-cost hardware  
- Analyzing scalability of distributed monitoring systems  
- Comparing threshold-based detection with more advanced techniques  

---

## 💡 Motivation

This project aligns with my long-term goal of working in cybersecurity, particularly in SOC and blue-team roles.

It combines:
- Practical log analysis  
- Security monitoring  
- Systems design  
- Infrastructure planning  
- Real-world simulation  

---

## 📎 Status

🚧 In active development — Phase 1 (Log Analysis Engine)

---

## 🤝 Contributions

This is currently a personal academic and research project. Feedback, suggestions, and discussions are welcome.

---

## 📜 License

TBD
