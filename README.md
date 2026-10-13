# Paylink 💳

Paylink is a web application designed to integrate seamless M-Pesa payments using the Safaricom Daraja API.

## 🚀 Features
* **Simple Interface:** Clean form to capture the user's phone number and transaction amount.
* **Instant STK Push:** Triggers an automatic M-Pesa prompt directly to the user's mobile phone.
* **Seamless Payment Flow:** Enables fast, secure user authorization via M-Pesa PIN input.

## 🛠️ How It Works
1. User enters their phone number and payment amount on the Paylink web interface.
2. The server initiates an STK Push request via the Safaricom Daraja API.
3. The user receives a pop-up on their phone requesting their M-Pesa PIN.
4. Upon entering the correct PIN, the payment is processed and finalized in real time.

## 🧰 Tech Stack
* **Frontend:** HTML, CSS, JavaScript
* **Backend Integration:** Node.js / Express (Safaricom Daraja API - STK Push)

