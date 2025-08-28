# 🔒 CyberSec_Trojan_Sim

An **educational surveillance tool** built in Python that demonstrates how adversaries may capture sensitive data.  
This project simulates trojan-like surveillance techniques for **cybersecurity learning, red-team exercises, and malware research** in a **controlled lab environment** only.  

⚠️ **Disclaimer**: This project is strictly for **educational purposes**.  
Unauthorized use against individuals or systems without consent is **illegal and unethical**.  
The author is not responsible for misuse.

---

## Features
- 📷 **Webcam Capture** – Take a snapshot using the system webcam  
- 📋 **Clipboard Sniffer** – Extract current clipboard contents  
- 💻 **System Info Extractor** – Gather system and hardware details  
- 🖼️ **Screenshot Grabber** – Capture the desktop screen view  
- 🎙️ **Audio Recorder** – Record microphone input (configurable duration)  
- 📂 **Data Export** – Save outputs in text and media files  
- ⏳ **Execution Delay** – Wait before collection begins (default: 10s)  

---

## Technologies Used
- 🐍 Python 3  
- 🖼️ OpenCV (`opencv-python`)  
- 🖱️ PyAutoGUI  
- 🎵 SoundDevice, SciPy  
- ⚙️ Platform, Socket, UUID, Psutil  
- 🗔 Tkinter (optional for GUI file dialog)  

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Gustav1814/CyberSec_Trojan_Sim.git
cd CyberSec_Trojan_Sim
```
### 2. Install Requirements
```bash
pip install -r requirements.txt
```
### 4. Run the Tool
```bash
python main.py
```
---
By default, the tool waits 10 seconds before capturing data.
You can adjust this in the time.sleep() call inside main.py.
---

## Output Files
- 📝 system_info.txt – System hardware & network details
- 📑 clipboard.txt – Clipboard contents
- 🖼️ screenshot.png – Desktop screenshot
- 📷 webcam.png – Webcam snapshot
- 🎙️ audio.wav – Microphone audio recording
---

##📦 CyberSec_Trojan_Sim
 ┣ 📜 main.py
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┣ 📂 outputs
 ┃ ┣ 📜 system_info.txt
 ┃ ┣ 📜 clipboard.txt
 ┃ ┣ 🖼️ screenshot.png
 ┃ ┣ 📷 webcam.png
 ┃ ┗ 🎙️ audio.wav
---
Ethical Considerations

## This project is intended for:
- 🎓 Cybersecurity education
- 🧪 Malware behavior research (in sandbox/lab)
- 🛡️ Understanding red-team surveillance methods
---
❌ Do not use this on personal or third-party systems without explicit consent.
Such actions are a violation of privacy laws and may result in severe legal consequences.
---
## Author
- ZEERAK SHAHZAD
- 🎓 BS Cybersecurity
- 🏫 National University of Computer and Emerging Sciences (FAST)
