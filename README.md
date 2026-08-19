# 🎂 Birthday Wisher

**Birthday Wisher** is a Python-based automation project that automatically sends personalized birthday wishes through email. The application checks a CSV file for birthdays matching the current date, selects a random birthday letter template, replaces the `[NAME]` placeholder with the birthday person's name, and sends the personalized message using Gmail SMTP.

Built with **Python**, **Pandas**, **datetime**, **random**, and **smtplib**, this project demonstrates how Python can be used to automate repetitive tasks and send personalized emails.

---

## 📸 Screenshots
<img width="258" height="231" alt="Screenshot 2026-08-19 165600" src="https://github.com/user-attachments/assets/d3e8eea1-e29f-4c55-a922-a8754d5aac8f" />


### Birthday Data

The application reads birthday information from a CSV file containing:

- Name
- Email
- Birth year
- Birth month
- Birth day

### Birthday Email

The application automatically sends a personalized birthday email using one of the available letter templates.

---

## ✨ Features

- 🎂 Automatically detects birthdays
- 📅 Checks the current date
- 📂 Reads birthday information from a CSV file
- 🎲 Randomly selects a birthday letter template
- ✍️ Automatically replaces `[NAME]` with the birthday person's name
- 📧 Sends personalized birthday emails
- 🔐 Uses Gmail SMTP with STARTTLS
- 📊 Uses Pandas for CSV data processing
- ⚡ Lightweight and easy to use
- 🤖 Automates the birthday wishing process

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — CSV data processing
- **datetime** — Current date handling
- **random** — Random letter template selection
- **smtplib** — Email sending through Gmail SMTP

---

## 📁 Project Structure

```text
Birthday-Wisher/
│
├── birthday-wisher-normal-start/
│   └── main.py
│
├── letter_templates/
│   ├── letter_1.txt
│   ├── letter_2.txt
│   └── letter_3.txt
│
├── birthdays.csv
├── README.md
└── requirements.txt

---

## 📧 Gmail Configuration

This project uses Gmail's SMTP server to send birthday emails.

SMTP Configuration
SMTP Server : smtp.gmail.com
Port        : 587
Security    : STARTTLS
