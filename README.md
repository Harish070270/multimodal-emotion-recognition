# Multimodal Emotion Recognition System

A real-time **multimodal emotion recognition system** that analyzes **facial expressions** from a webcam and **speech signals** from a microphone to infer human emotional states.  
The system combines visual and audio cues using **decision-level fusion** to improve robustness and reliability.

---

## Overview

Emotion recognition based on a single modality often suffers from ambiguity and noise.  
This project addresses that limitation by integrating **computer vision** and **audio signal processing**, enabling more accurate and context-aware emotion prediction.

The application captures **video and audio simultaneously for a fixed duration**, processes each modality independently, and fuses the results to produce a final emotion classification.

---

## Key Features

- Real-time webcam-based facial emotion recognition  
- Microphone-based audio capture for emotion analysis  
- Synchronized multimodal data acquisition  
- Confidence-aware decision-level fusion  
- Interactive and user-friendly web interface  
- Modular and extensible system design  

---

## Technology Stack

- **Language:** Python 3.10  
- **Web Framework:** Streamlit  
- **Computer Vision:** OpenCV  
- **Facial Emotion Model:** DeepFace (pretrained CNN models)  
- **Audio Processing:** SoundDevice, SciPy  
- **Environment Management:** Python Virtual Environment  

---

## System Architecture

1. User initiates multimodal capture through the UI  
2. Webcam captures facial frames  
3. Microphone records speech for a predefined duration  
4. Facial emotion is inferred using pretrained deep learning models  
5. Audio emotion is processed independently  
6. A fusion module combines both predictions based on confidence rules  
7. Final emotion output is displayed to the user  

---

## Installation and Setup

### 1. Clone the repository
```bash
git clone <repository-url>
cd multimodal-emotion-recognition
