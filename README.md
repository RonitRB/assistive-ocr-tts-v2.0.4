# Assistive Technology for Visually Impaired Students (NAIN 2.0)

## 📌 Project Overview

This project focuses on developing an **Assistive Technology System for Visually Impaired Students** that enables real-time auditory access to classroom board content. The system captures text written on classroom boards (blackboard, whiteboard, or projected digital content), converts it into readable text using Optical Character Recognition (OCR), and then converts the text into speech using a Text-to-Speech (TTS) engine.

The spoken output is delivered wirelessly to the student through a Bluetooth audio device (earbuds or headphones), allowing visually impaired students to follow classroom teaching independently and in real time.

This project is developed under **NAIN 2.0**, a Karnataka State Government–funded innovation initiative.

---

## 🎯 Problem Statement

Visually impaired students often depend on:

- Human assistance
- Post-class notes
- Limited accessibility tools

These methods do not provide **real-time access** to what teachers write on classroom boards. Existing OCR tools are mostly document-based or mobile-dependent and are not optimized for live classroom environments.

---

## 💡 Proposed Solution

The proposed system introduces a **real-time classroom OCR-to-TTS pipeline** using edge AI.

### System Workflow

1. A high-resolution camera captures live images of the classroom board.
2. Images are processed locally on a Jetson Orin Nano.
3. OCR algorithms extract handwritten and digital text.
4. Extracted text is converted into speech using TTS.
5. Audio output is transmitted to the student via Bluetooth earbuds/headphones.

---

## 🧠 Key Features

- 📷 Single high-resolution centralized camera
- ⚡ Real-time OCR processing
- ✍️ Supports handwritten & digital text
- 🗣️ Text-to-Speech conversion
- 🎧 Wireless Bluetooth audio output
- 🧠 Edge AI processing (offline capable)
- 🏫 Designed specifically for classroom environments
- ♿ Non-intrusive assistive learning experience

---

## 🛠️ Hardware Requirements

- NVIDIA Jetson Orin Nano Developer Kit
- High-resolution camera (1080p or higher)
- Bluetooth audio device (earbuds/headphones)
- Stable power supply

---

## 🧩 Software Requirements

- Python 3.x
- OpenCV
- OCR Engine (e.g., PaddleOCR / Tesseract)
- Text-to-Speech Engine
- Bluetooth audio stack
- NVIDIA JetPack (for Jetson)

---

## 📐 System Architecture

Camera
   ↓
Jetson Orin Nano
   ↓
Image Preprocessing
   ↓
OCR (Handwritten + Digital Text)
   ↓
Text Processing
   ↓
Text-to-Speech
   ↓
Bluetooth Audio Output

---

## 🚀 Installation & Setup (Basic)

```bash
git clone https://github.com/RonitRB/assistive-ocr-tts-v2.0.4.git
cd assistive-ocr-tts-v2.0.4
pip install -r requirements.txt
python main.py

---

⚠️ Note: Ensure the camera and Bluetooth audio device are properly connected and configured.

🧪 Current Status
- ✅ OCR-to-TTS pipeline implemented
- ✅ Digital text detection working
- 🚧 Handwritten board text optimization ongoing
- 🚧 Final hardware integration in progress
- 🚧 Classroom testing phase ongoing

📅 Project Timeline
- Development Phase: Completed
- Final Testing & Hardware Integration: Ongoing
- Invention Disclosure Submission: 15th February 2026

📜 Intellectual Property
This project is part of **NAIN 2.0** (New Age Incubation Network), a Government of Karnataka-funded initiative.

Patent filing and IP protection are planned prior to public dissemination.

👥 Team
- Ronit Bongale (GitHub: [RonitRB](https://github.com/RonitRB), LinkedIn: [Ronit Bongale](https://www.linkedin.com/in/ronit-bongale/))
- Krishna Pawar (GitHub: [krishnapawar05](https://github.com/krishnapawar05), LinkedIn: [Krishna Pawar](https://www.linkedin.com/in/krishnapawar05/))
- Shakuntala Saunshi (GitHub: [Shakuntalas](https://github.com/Shakuntalas), LinkedIn: [Shakuntala Saunshi](https://www.linkedin.com/in/shakuntala-saunshi/))

🤝 Acknowledgements
- Government of Karnataka – NAIN 2.0
- Department of Computer Science & Engineering
- Project mentors and faculty advisors
- Open-source software contributors

🔮 Future Enhancements
- Improved handwriting recognition
- Multilingual OCR and TTS
- Mathematical symbol recognition
- Multiple student audio support
- Smart classroom integration

📬 Contact
For queries or collaboration:

**GitHub:** [RonitRB](https://github.com/RonitRB)
**LinkedIn:** [Ronit Bongale](https://www.linkedin.com/in/ronit-bongale/)
