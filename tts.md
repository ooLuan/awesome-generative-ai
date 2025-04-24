# 🔊 Text-to-Speech (TTS) Models

Curated list of high-quality open-source TTS models and toolkits used for research, production, and multi-language synthesis.

---

## 🐢 Tortoise-TTS
- [Repo](https://github.com/neonbjb/tortoise-tts)
- High-fidelity voice cloning and generation
- Supports prompt tuning and long-form speech
- Requires GPU and large memory (≥16GB recommended)

---

## 🗣️ VITS (Variational Inference TTS)
- [Repo](https://github.com/jaywalnut310/vits)
- End-to-end model combining Tacotron2 + HiFi-GAN
- High-quality synthesis with fewer artifacts
- Fast training and inference

---

## 🐸 Coqui TTS
- [Repo](https://github.com/coqui-ai/TTS)
- Modular, multilingual, production-ready toolkit
- Easy training and fine-tuning on your voice
- Offers pretrained models (English, German, French, etc.)

---

## 🎙️ Tacotron 2
- [TensorFlow Tacotron 2](https://github.com/Rayhane-mamah/Tacotron-2)
- Two-stage pipeline: spectrogram prediction + vocoder
- Realistic prosody and intonation

---

## ⚡ FastSpeech 2
- [Repo](https://github.com/ming024/FastSpeech2)
- Non-autoregressive TTS with high speed and stability
- Commonly used with vocoders like HiFi-GAN or WaveGlow

---

## 🧠 Glow-TTS
- [Repo](https://github.com/jaywalnut310/glow-tts)
- Flow-based TTS architecture
- High-performance and parallelizable

---

## 🔊 Vocoders (Used with Spectrogram Models)

- [HiFi-GAN](https://github.com/jik876/hifi-gan): Fast, high-quality vocoder
- [WaveGlow](https://github.com/NVIDIA/waveglow): Real-time waveform generator
- [MelGAN](https://github.com/descriptinc/melgan-neurips): GAN-based vocoder

---

💡 **Tip**: Combine Tacotron2/FastSpeech2 with HiFi-GAN for clean, real-time voice synthesis.

