# Deepfake_audio_detection_system
A mini project made for detecting deepfake audio using dsp techniques
# 🔊 Deepfake Audio Detection using DSP

## 📌 Project Description
This project focuses on detecting whether an audio signal is a **real human voice** or an **AI-generated (deepfake) voice** using **Digital Signal Processing (DSP)** techniques.

With the rapid advancement of AI-based voice synthesis, it has become difficult to distinguish between real and fake audio. This project aims to solve this problem by analyzing audio signals in both **time domain** and **frequency domain**.

---

## ⚙️ Methodology

The system processes two audio files and performs the following steps:

### 1. Preprocessing
- Converts audio to mono
- Normalizes amplitude
- Removes silence regions

### 2. Frequency Analysis (FFT)
- Converts signal from time domain to frequency domain
- Helps analyze frequency components of audio

### 3. Feature Extraction
The following DSP features are extracted:

- **Spectral Flatness** → Measures randomness vs tonal nature  
- **Zero Crossing Rate (ZCR)** → Measures signal variation  
- **Harmonic Variation** → Measures irregularity in frequency peaks  
- **Energy** → Represents signal strength  

### 4. Classification
- Features are combined using weighted scoring
- Audio is classified as:
  - 🎤 Human Voice  
  - 🤖 AI Generated Voice  

---

## 📊 Output

The system provides:

- Feature comparison table  
- Final classification result  
- Decision explanation  
- Graphical visualization:
  - Time-domain waveform  
  - Frequency spectrum (FFT)  
  - Spectrogram (time-frequency analysis)  
  - Feature comparison graph  

---

## 🎯 Key Idea

Human speech is naturally **irregular and dynamic**, while AI-generated speech tends to be more **structured and consistent**.  
These differences are captured using DSP features for classification.

---

## 🛠️ Tools Used

- MATLAB  
- Digital Signal Processing (FFT, ZCR, Spectral Analysis)

---

## 🚀 Applications

- Deepfake detection  
- Cybersecurity  
- Voice authentication  
- Media verification  

---

## 📌 Conclusion

This project demonstrates how fundamental DSP techniques can be used to analyze and classify audio signals.  
It provides a simple and effective approach for detecting AI-generated voices.

---
