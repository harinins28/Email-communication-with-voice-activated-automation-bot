# Email communication with voice activated automation bot
The "Voice-Activated Email Automation Bot" uses Speech Recognition and pyAudio to enable voice-controlled email composition and sending. It offers accurate speech-to-text conversion, integration with popular email clients, and secure handling of data.
# Voice Activated Email Automation Bot

## Overview
The Voice Activated Email Automation Bot is a Python application that enables users to send emails using voice commands. This bot listens to the user's voice input, processes it, and sends an email accordingly. It is built using libraries such as `smtplib`, `speech_recognition`, and `pyttsx3`.

## Features
- Voice recognition to capture email details.
- Text-to-speech to communicate with the user.
- Email sending through a specified SMTP server.

## Prerequisites
- Python 3.x
- An internet connection
- A microphone
- An email account (Outlook in this case)

## Installation
1. Clone the repository or download the script.
2. Install the required libraries:
    ```sh
    pip install smtplib speechrecognition pyttsx3
    ```

## Setup
1. Ensure your email account has the necessary permissions to allow app access.
2. Modify the `server.login` method in the `send_email` function with your email and password.

## Usage
1. Run the script:
    ```sh
    python voice_email_bot.py
    ```
2. Follow the voice prompts to:
    - Specify the recipient (by their nickname).
    - State the subject of the email.
    - Dictate the content of the email.

## Notes
- Ensure your microphone is working correctly.
- The email addresses in the `email_list` dictionary should be updated with actual email addresses.
- The script currently uses a hardcoded email and password for sending emails. For production use, consider implementing a more secure authentication method.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
