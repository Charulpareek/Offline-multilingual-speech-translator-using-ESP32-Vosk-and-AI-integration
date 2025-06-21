
# 🔊 AIOT Project – Offline multilingual speech translator using ESP32, Vosk, and AI integration

This project implements a **low-cost, real-time, multilingual speech translation system** that works **offline** using an ESP32 microcontroller and AI-powered translation tools.

---

## 📚 About the Project

- **Title**: Real-Time Multilingual Voice Translator with ESP32 and AI Integration  
- **Domain**: Artificial Intelligence, Internet of Things, Embedded Systems  
- **Languages Supported**: English, Hindi, Telugu  
- **Focus**: Offline Speech Translation, Edge AI, Embedded NLP  

---

## 🔍 Objectives

- Enable real-time offline voice translation.
- Use ESP32 + I2S Mic + MAX98357A DAC for audio input/output.
- Handle STT, translation, and TTS on a local server without internet dependency.
- Ensure privacy and scalability in low-connectivity environments.

---

## 🧠 Technologies Used

- **Microcontroller**: ESP32 (MicroPython)
- **Audio Hardware**: INMP441 Digital Mic, MAX98357A DAC, 3W Speaker
- **Speech Recognition**: Vosk (offline STT)
- **Translation**: Argos Translate (offline NMT)
- **Speech Synthesis**: pyttsx3 (offline TTS)
- **Server Backend**: Python, Flask
- **Communication**: HTTP, Wi-Fi

---

## 📄 Documentation

All supporting documents are stored in the [`Documentation/`](./Documentation/) folder.

| Document Type          | File Name                                                                       | Description                         |
|------------------------|----------------------------------------------------------------------------------|-------------------------------------|
| 📘 Project Report       | [PROJECT_REPORT[1].docx](./Documentation/PROJECT_REPORT[1].docx)                 | Detailed explanation of the project |
| 📄 Research Paper       | [ResearchPaper-Team-11.docx](./Documentation/ResearchPaper-Team-11.docx)         | Technical research paper            |
| 🖼️ Project Poster       | [aiot poster 2.pptx](./Documentation/aiot%20poster%202.pptx)                     | Poster for presentation             |
| 📊 Final Presentation   | [PPT Presentation-(Team-11).pptx](./Documentation/PPT%20Presentation-(Team-11).pptx) | Final project presentation slides   |

## 🧩 Hardware Connections

### 🔌 ESP32 Pin Connections

| Component         | ESP32 Pin       | Description                            |
|------------------|------------------|----------------------------------------|
| **INMP441 Mic**   |                  |                                        |
| VCC              | 3.3V             | Power                                  |
| GND              | GND              | Ground                                 |
| SCK              | GPIO 14          | Bit Clock                              |
| WS               | GPIO 15          | Word Select (L/R Clock)                |
| SD               | GPIO 32          | Serial Data (mic output)               |
| **MAX98357A DAC** |                  |                                        |
| VIN              | 5V               | Power                                  |
| GND              | GND              | Ground                                 |
| LRC              | GPIO 25          | L/R Clock                              |
| BCLK             | GPIO 26          | Bit Clock                              |
| DIN              | GPIO 22          | Digital Audio In from ESP32            |
| **Speaker**       | DAC Output       | 3W speaker connected to MAX98357A      |

---

### 🧠 ESP32 Circuit Diagram
![image](https://github.com/user-attachments/assets/12746648-dd57-489b-9a16-a2cb0dcb836d)


## 🔌 Hardware Setup
![WhatsApp Image 2025-06-21 at 13 58 32_4b5ef713](https://github.com/user-attachments/assets/21991b89-627d-40d4-9688-4e84bf2a5bcf)










