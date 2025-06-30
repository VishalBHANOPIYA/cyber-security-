# Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
The goal of this task was to capture live network traffic using **Wireshark**, identify key protocols,
and analyze the data exchanged — especially observing how form data (like login credentials) can be captured if the connection is unencrypted (HTTP).

---

## 🧰 Tools Used
- **Wireshark** (Packet Capture and Analysis Tool)
- **Kali Linux** (Host OS)
- **Test Web Application**

---

## 🌐 Network Setup
- **Interface Used**: `wlan0`
- **Filter Applied**: `http`  
- **Target URLs**:
  - Login page: `/login.php`
  - Form submission page: `/userinfo.php`

---

## 🔍 Protocols Identified
- **HTTP**: Captured form submissions in plaintext
- **TCP**: Underlying transport protocol used
- **OCSP**: (Observed from other traffic, part of TLS/SSL checking)

---

## 🧠 Key Takeaways
- HTTP is not encrypted — any sensitive data sent can be captured using Wireshark.
- Packet sniffing allows attackers to extract login info or personal details if proper security (HTTPS) is not used.
- Always prefer secure protocols like **HTTPS** to protect user data.

---

## ✅ Status
✔️ Task Completed  
📤 Submitted to GitHub  
📁 Ready for evaluation
