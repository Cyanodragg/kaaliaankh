# 🎯 Kaaliaankh (BlackEye) - Phishing via Email

**Kaaliaankh** is a social engineering and phishing simulation tool built for cybersecurity research and ethical hacking training. It generates fake login pages and provides a disguised phishing link that can be used in **email-based clickjacking** scenarios to demonstrate real-world phishing attacks.

> ⚠️ **Note:** This tool is for **educational purposes only**. Unauthorized use against real individuals or systems is **strictly prohibited** and punishable under law.

---

## 🧠 Project Highlights

- Creates a **fake login page** (Facebook, Gmail, Instagram, etc.)
- Generates a **phishing URL** (local or tunneled) disguised to look legitimate
- Supports **clickjacking attacks** (e.g., invisible iframe trick)
- Can be sent via **email** to simulate phishing attacks
- Captures target credentials in real-time

---

## ⚙️ How It Works

1. Run the tool (`./1.sh`)
2. Select your phishing page template (e.g., Facebook)
3. A **fake link** is generated (e.g Local Host)
4. You embed this link in a crafted **email** using social engineering
5. When the target clicks the link, a fake login page opens (possibly hidden inside a **clickjacked iframe**)
6. If the target enters credentials, they are captured and saved locally
