# 🎙️ Python Voice-Controlled Ad Skipper

This project is a simple Python automation tool that listens for a hotword (like **"Ganesha"**) and automatically skips YouTube ads by simulating a mouse click. It's helpful if you're multitasking or away from your keyboard but still want to skip ads without touching anything.

---

## 🚀 Features

- 🎧 Listens for your voice command using the microphone
- 🖱️ Simulates mouse movement and clicks the "Skip Ad" button
- ⏳ Adds a short wait to ensure the button is visible
- 🔁 Repeats up to 15 times or until manually stopped

---

## 🛠️ Tech Stack

- **speech_recognition** – Converts voice to text
- **pyautogui** – Automates mouse movement and clicking
- **time** – Adds delays between actions

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/python-voice-ad-skipper.git
cd python-voice-ad-skipper
