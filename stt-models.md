# 🧠 Speech-to-Text (STT) Models

A curated list of open-source and production-ready STT models, libraries, and tools for offline and real-time transcription.

---

## 🔥 Whisper-Based Models

### 🔷 [OpenAI Whisper](https://github.com/openai/whisper)
- Multilingual and multitask ASR (speech recognition, translation, language ID)
- Trained on 680,000 hours of web audio
- Easy-to-use CLI and Python API

### 🔷 [faster-whisper](https://github.com/SYSTRAN/faster-whisper)
- Optimized for fast inference using CTranslate2
- Great for deployment with CPU/GPU/edge devices
- Drop-in replacement for Whisper in many pipelines

### 🔷 [WhisperX](https://github.com/m-bain/whisperX)
- Whisper + word-level timestamps + speaker diarization
- Uses PyAnnote for speaker separation

---

## ⚙️ Traditional & Real-Time STT Engines

### 🔷 [Kaldi](https://github.com/kaldi-asr/kaldi)
- Gold standard for academic speech recognition research
- Powerful but requires complex setup and configuration
- Extensive support for custom ASR pipelines

### 🔷 [Vosk API](https://github.com/alphacep/vosk-api)
- Real-time STT for 20+ languages
- Works offline on Android, Raspberry Pi, and desktops
- Very lightweight and fast

### 🔷 [DeepSpeech (Mozilla)](https://github.com/mozilla/DeepSpeech)
- End-to-end STT engine based on TensorFlow
- Trained on English datasets (LibriSpeech, Common Voice)

---

## 🧠 PyTorch-Based Frameworks

### 🔷 [SpeechBrain](https://github.com/speechbrain/speechbrain)
- All-in-one speech toolkit: ASR, speaker ID, enhancement, separation, etc.
- PyTorch-based and well-documented
- Pretrained models for many use cases

### 🔷 [RealtimeSTT](https://github.com/KoljaB/RealtimeSTT)
- Simple pipeline for real-time transcription from microphone
- Lightweight and built for Python

---

## 🧪 Lightweight & Embedded STT

### 🔷 [Silero Models](https://github.com/snakers4/silero-models)
- Production-ready models for mobile and edge devices
- Supports multiple languages (English, Russian, etc.)
- Works with ONNX, TFLite, TorchScript

### 🔷 [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)
- Cross-platform real-time ASR using ONNX backend
- Inspired by Kaldi and k2 projects

---

## 📚 Utility Libraries

### 🔷 [speech_recognition (Python)](https://github.com/Uberi/speech_recognition)
- Unified API to access Google Web Speech, CMU Sphinx, Wit.ai, etc.
- Suitable for simple applications or prototyping

### 🔷 [annyang (JS)](https://github.com/TalAter/annyang)
- Lightweight voice command library for browser apps

---

💡 **Tip**: Choose models based on your deployment target (server, mobile, edge) and language coverage needs.

