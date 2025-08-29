# 🔐 Secure Login System with Password and OTP Verification

This project is a **Python-based login system** that requires a **password** 🔑 and a **One-Time Password (OTP)** 📲 for authentication.  
The OTP is generated dynamically and sent to the user’s phone number using the **Twilio SMS API** ☁️.

---

## ✨ Features

- 🔑 **Password Authentication**
  - User must enter the correct password within a limited number of attempts.
  - Maximum attempts are configurable (`max_attempts`).

- 📲 **OTP Verification**
  - Once the password is correct, a **6-digit OTP** is generated.
  - OTP is sent to the user’s phone via **Twilio SMS API**.
  - User must enter the correct OTP to gain access.

- 🛡️ **Security**
  - Prevents brute force by locking the user out after maximum failed attempts.
  - OTP is unique 🔢 for each login attempt.

---


