# 🔐 Web Application Firewall (WAF) Lab using SafeLine

## 📌 Overview

This project demonstrates how a Web Application Firewall (WAF) protects a vulnerable web application (DVWA) from common attacks such as SQL Injection and HTTP Flood (Rate Limiting).

## 🛠️ Tools Used

* Ubuntu (Virtual Machine)
* Docker & Docker Compose
* DVWA (Damn Vulnerable Web Application)
* SafeLine WAF



## ⚙️ Setup

Refer: `docs/setup.md`

## 🔍 Attack Demonstration

### SQL Injection

Payload used:
`1' OR '1'='1`

* Attack successful without WAF
* Blocked after enabling WAF

➡️ Detailed analysis: `docs/attack-analysis.md`

## 🚦 Rate Limiting

* Configured HTTP Flood protection
* Simulated multiple rapid requests
* WAF restricted excessive traffic

➡️ Details: `docs/rate-limiting.md`



## 🎯 Key Learnings

* SQL Injection attack behavior
* WAF detection & blocking
* Log analysis
* Rate limiting concepts

## 👨‍💻 Author
Saketh Kumar 
