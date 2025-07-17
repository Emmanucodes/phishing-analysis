# 📧 Phishing Email Analysis (Beginner-Level Project)

This project is part of my cybersecurity learning journey, focusing on how phishing emails work and how to analyze them safely. I’m documenting my process as I learn the skills required to become a SOC Analyst.

> 🚧 This project is currently in progress. I will update this README as I go deeper into the analysis.

---

## 🎯 Goal

To understand how phishing emails are structured, how **malicious PDF attachments** work, and how to analyze them safely using free tools and techniques.

---

## 🛠 Tools I Plan to Use

- 🧪 [VirusTotal](https://virustotal.com) – to scan the PDF file
- 🐍 `pdfid.py` & `pdf-parser.py` – for static analysis of the PDF
- 🖥️ Virtual Machine – for safe analysis (I’m using Windows VM)
- 📧 Email header inspection (manual or tool-based)
- 🔍 Optional: Sandboxing tools (e.g., Any.Run, Hybrid Analysis)

---

## 🕵️‍♂️ Current Progress

- ✅ Found a phishing email sample with a `.pdf` attachment
- ✅ Opened the file in a **safe virtual machine**
- ✅ Scanned the file using VirusTotal
- 🔄 Planning to run static analysis using `pdfid.py` and `pdf-parser.py`
- 🔄 Will extract any embedded links or scripts
- 🔄 Will document the email headers and phishing intent

---

## 📘 What I’ve Learned So Far

- PDF files can contain malicious scripts, links, or embedded actions
- Even “simple-looking” documents can lead to phishing websites or malware
- Always inspect suspicious files in a controlled, isolated environment
- Email spoofing can make phishing messages look trustworthy

---

## 🧑‍💻 Author

**Emmanuel Ajayi**  
Aspiring SOC Analyst | Cybersecurity Enthusiast  
[LinkedIn](https://www.linkedin.com/in/emmanuel-ajayi-gbenga)  
[GitHub](https://github.com/Emmanucodes)

---

## ⚠️ Disclaimer

This project is for educational purposes only. Do not run suspicious files on your main device. Always use a VM or sandbox environment.
