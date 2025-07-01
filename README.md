# Email Automation with Python

This project allows you to send emails using your voice via Python. It uses `speech_recognition`, `pyttsx3`, and `smtplib`.

## Features
- Voice-controlled input for recipient, subject, and message
- Gmail integration using App Passwords
- Simple JSON file for contact management

## Requirements
```bash
pip install pyttsx3 speechrecognition
📁 Bonus: Folder Project Structure

email_automation/
│
├── main.py
├── contacts.json       # for saving name-email pairs
├── README.md
