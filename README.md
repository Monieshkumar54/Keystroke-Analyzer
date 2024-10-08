## Keystroke Analyzer

## Overview

The Keystroke Analyzer is a Python script that captures and analyzes keystrokes on a computer. It uses the pynput library to monitor keyboard events and sends the captured keystrokes to a specified email address using the smtplib library.


## Features

Captures keystrokes in real-time

Sends captured keystrokes to a specified email address

Ignores special keys (e.g., Shift, Ctrl, Alt)

Replaces space keys with literal space characters

Limits the number of keystrokes sent in each email to 10
## Requirements

Python 3.x

pynput library (install with pip install pynput)

smtplib library (built-in Python library)

ssl library (built-in Python library)

A Gmail account (for sending emails)

## Usage

Install the pynput library by running pip install pynput in your terminal.

Create a new Python file (e.g., keystroke_analyzer.py) and copy the script into it.

Replace "your - email - here" with your Gmail address in the sendEmail function.

Replace "enter your password" with your Gmail password in the sendEmail function.

Run the script by executing python keystroke_analyzer.py in your terminal.

The script will start capturing keystrokes and sending them to your specified email address.

## Note

This script is for educational purposes only and should not be used to monitor or track keystrokes without the user's consent.

Make sure to use a secure password and consider enabling two-factor authentication for your Gmail account.

This script may not work if you have two-factor authentication enabled for your Gmail account.

## Screenshots
![WhatsApp Image 2024-09-25 at 5 34 39 PM](https://github.com/user-attachments/assets/5bee3137-bf24-4b91-8e3b-90849fa4e8fd)

![WhatsApp Image 2024-09-25 at 5 34 39 PM (1)](https://github.com/user-attachments/assets/dbefed26-bbec-4a87-a65d-6953ca17a714)

![WhatsApp Image 2024-09-25 at 5 34 39 PM (2)](https://github.com/user-attachments/assets/a1585e85-1b7f-4233-9eaf-3cf72695b1aa)
