# 💻 Smart Mirror Voice Assistant

This project is a multilingual **Smart Mirror system** built using **Raspberry Pi 3** and **Pygame**, capable of voice interaction, department-specific guidance, and QR code display. It simulates an information assistant for smart campuses.

---

## 🎯 Features

- 🗣️ Voice-activated commands ("hello", "namaste")
- 🌐 Language selection (English, Kannada, Hindi, etc.)
- 🧭 Branch/location guidance with:
  - Audio prompts
  - Image display
  - QR code generation
- 🔁 Idle looping video/slideshow until voice input is detected
- 💻 Full-screen GUI using **Pygame**

---

## 🧠 How It Works

1. The mirror starts in **idle mode**, looping a video or slideshow
2. Upon detecting a voice trigger like **"hello"** or **"namaste"**, it:
   - Switches to active mode
   - Prompts for language choice
3. Based on the language and branch selection:
   - Displays a mapped image (e.g., department or location)
   - Plays the corresponding audio
   - Shows a **QR code** for navigation or info

---

## 🖼️ Outputs

### 🔹 Welcome Screen (Idle)
<p align="center">
  <img src="outputs/welcome_screen.png" width="400"/>
</p>

---

### 🔹 Branch Selection Interface
<p align="center">
  <img src="outputs/branch_selection.png" width="400"/>
</p>

---

### 🔹 QR Code Display Demo
<p align="center">
  <img src="outputs/qr_display_demo.gif" width="400"/>
</p>

---

## 🗂️ Project Structure

- `/code`: Python files for UI logic, speech recognition, and asset handling
- `/assets`: Audio, image, video, and QR assets mapped by branch/language
- `/outputs`: Screenshots and GIF demos of UI

---

## 🔧 Technologies Used

- Raspberry Pi 3
- Python 3
- Pygame
- `speech_recognition`, `pygame`, `pillow`, `qrcode` libraries

---

## 📄 License

Licensed under the [MIT License](LICENSE)
