# 📧 Phishing Email Analysis (Beginner-Level Project)

This project is part of my cybersecurity learning journey, focusing on how phishing emails work and how to analyze them safely. I’m documenting my process as I learn the skills required to become a SOC Analyst.

> 🚧 This project is currently in progress. I will update this README as I go deeper into the analysis.

---

## 🎯 Goal

To understand how phishing emails are structured, how malicious attachments work, and how to analyze them safely using free tools and techniques.

---

## 🛠 Tools I Plan to Use

- 🧪 [VirusTotal](https://virustotal.com) – to scan attachments
- 🧵 `strings` command – to inspect file content
- 🖥️ Virtual Machine – for safe analysis (I’m using Windows VM)
- 📧 Email header inspection (manual or tool-based)
- 🔍 Optional: Sandboxing tools later (e.g., Any.Run, Hybrid Analysis)

---

## 🕵️‍♂️ Current Progress

- ✅ Found a phishing email sample with a `.lnk` attachment
- ✅ Opened the file in a **safe virtual machine**
- 🔄 Planning to scan the file on VirusTotal
- 🔄 Will inspect the `.lnk` file with `strings` and check for PowerShell commands or IOCs
- 🔄 Will document the email headers and body content

---

## 📘 What I’ve Learned So Far

- `.lnk` files (Windows shortcuts) can be used to run hidden malicious scripts
- It’s important to always analyze suspicious files in an isolated environment
- VirusTotal is a great starting point for scanning unknown files
- Phishing emails can appear to come from trusted sources

---

## 🧑‍💻 Author

**Emmanuel Ajayi**  
Aspiring SOC Analyst | Cybersecurity Enthusiast  
[LinkedIn](https://www.linkedin.com/in/emmanuel-ajayi-gbenga)  
[GitHub](https://github.com/Emmanucodes)

---

## ⚠️ Disclaimer

This project is for educational purposes only. Do not run suspicious files on your main device. Always use a VM or sandbox environment.

