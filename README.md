# FUTURE_CS_02
# 🎣 Phishing Simulation using Social Engineering Toolkit (SET)

> Simulating real-world phishing attacks to assess and enhance security awareness.

## 📌 Overview

This project demonstrates a **Credential Harvester Attack** using the powerful **Social Engineering Toolkit (SET)** on Kali Linux. The simulation was designed to evaluate how users interact with phishing content, analyze behavioral vulnerabilities, and propose security improvements for organizational defense.

---

## 🛠 Tools & Technologies

- **Operating System:** Kali Linux
- **Framework:** Social Engineering Toolkit (SET)
- **Web Server:** Apache2
- **Attack Vector:** Web-based Credential Harvester
- **Targeted Pages:** Cloned login interfaces (e.g., testphp.vulnweb.com, Instagram, Microsoft login)

---

## 🧪 Methodology

1. **SET Initialization**
   - Selected: *Social Engineering Attacks > Website Attack Vectors > Credential Harvester Attack Method*
2. **Web Server Configuration**
   - Apache2 used to serve cloned login pages
   - Local IP used as POST-back server: `http://192.168.221.74`
3. **Website Cloning**
   - Cloned real login pages using SET's site cloner
4. **Phishing Distribution**
   - Simulated phishing emails directing users to the fake pages
5. **Data Harvesting**
   - Captured submitted credentials via SET
   - Logged and analyzed user interaction

---

## 📊 Results Summary

> Credentials were captured and displayed in real-time through the SET console. Sensitive data has been sanitized for privacy.

---

## 🚧 Challenges Encountered

- Cloning modern, JavaScript-heavy sites (e.g., Instagram, Microsoft) caused delays and rendering issues.
- Apache port conflicts (port 80) required manual stopping of services.
- Some users demonstrated awareness, avoiding suspicious links.

## ✅ Recommendations

- Conduct regular phishing awareness training.
- Deploy Multi-Factor Authentication (MFA).
- Use email link inspection tools and awareness popups.
- Run periodic phishing simulations to measure improvement.

  ## Report Prepared by :
    Suryaganthan R
    Cybersecurity Student

