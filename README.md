# 🔐 Secure Data Encryption System

Welcome to the **Secure Data Encryption System** — a simple yet powerful 🔒 Streamlit app that lets you **securely store and retrieve sensitive data** using encryption and passkeys!

---

## ✨ Features

- 🔏 **Encrypt and Store Data** with a custom passkey
- 🔐 **Retrieve Data Securely** using the correct passkey
- ⚠️ **Failed Attempt Tracker** with lockout simulation
- 🔑 **Admin Reauthorization** via master password
- 🧠 Everything runs **in memory** — no external DB needed

---

## 🚀 How to Run

1. Make sure Python is installed (3.7+ recommended)
   
2. Install dependencies using pip:

```bash
pip install -r requirements.txt
```
3. Run the app:
```bash
streamlit run app.py
```

---

## 🛠️ Dependencies
* streamlit
* cryptography
You can install them easily using:
```bash
pip install streamlit cryptography
```

---

## 📂 File Structure
.
├── app.py
├── requirements.txt
└── README.md

---

## 🔐 Security Notes
* ⚠️ The encryption key is session-based. Restarting the app will reset all encrypted data.
* 🚫 No data is saved on disk — everything is in memory for privacy.
* 🔑 The master password (admin123) is hardcoded for demo purposes. Change this in production!

---

## 📧 Contact
For questions, suggestions, or feedback, feel free to reach out!

---

## ⭐ Give it a Star!
If you like this project, don’t forget to ⭐ the repo and share it with others!

---

## Connect with Me:
Name: Hamza Syed

Mail: hamzaaleem2302gmail.com
