# Talking-Calculator-2.0
Talking Calculator who can listen and recognize english speech and calculate too. 
🧮 Talking Calculator

Talking Calculator is a smart voice-powered calculator built with Python (Kivy, SpeechRecognition, Pyttsx3).
It supports normal math operations, speech recognition input, text-to-speech output, and light/dark themes.

✨ Features

🎤 Voice Input – Speak math expressions like “five plus six”

🗣 Voice Output – Speaks back results with natural TTS

🌙 Dark / Light Mode toggle

🔢 Standard Calculator Buttons

⚙️ Settings Page

📱 Works as a standalone desktop app (compiled with PyInstaller + Inno Setup)



🚀 Installation
1. From Installer (Windows)

Download the latest .exe from the Releases page and run the setup wizard.
It will install Talking Calculator with a desktop shortcut.

2. From Source (Developers)
# Clone repo
git clone https://github.com/yourusername/talking-calculator.git
cd talking-calculator

# Create virtual environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run app
python calculator.py

📦 Requirements

Python 3.8+

Kivy

SpeechRecognition

PyAudio

pyttsx3

Install with:

pip install kivy SpeechRecognition pyttsx3 pyaudio

🛠 Compilation

To build the app as .exe:

pyinstaller --noconsole --onefile --windowed calculator.py -n TalkingCalculator


Then create an installer with Inno Setup (installer script provided).

📄 License
Copyright © 2024 Tony the Tech Guy.  
All rights reserved.  

This software is provided "AS IS", without warranty of any kind.  
Personal and educational use only.  

👨‍💻 Author

Tony the tech guy aka Abdullah Ismail

GitHub: @tonythetechsavvy

