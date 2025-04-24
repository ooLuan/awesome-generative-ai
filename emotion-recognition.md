# set💬 Emotion Recognition

This section covers popular datasets and models used in speech and text-based emotion recognition systems.

---

## 🧪 Datasets

### 🎭 IEMOCAP

- Interactive emotional dyadic sessions (\~12 hours)
- Emotions: anger, happiness, sadness, frustration, neutral
- [Link](https://sail.usc.edu/iemocap/)

### 🎭 RAVDESS

- Ryerson Audio-Visual Dataset of Emotional Speech and Song
- Emotions: neutral, calm, happy, sad, angry, fearful, surprise, disgust
- [Link](https://zenodo.org/record/1188976)

### 🎭 CREMA-D

- Crowd-sourced Emotional Multimodal Actors Dataset
- Audio + video + ratings
- [Link](https://github.com/CheyneyComputerScience/CREMA-D)

---

## 🧠 Models

### 🧾 Text-Based (Korean, English)

#### KoBERT / KLUE-BERT

- Fine-tuned on call center or chat data
- Classifies emotions like joy, anger, sadness, etc.
- Use emoji filtering + text normalization for better results

#### RoBERTa / Electra

- Good for multilingual or cross-lingual emotion classification

---

### 🎧 Audio-Based

#### CNN + Mel-Spectrogram

- Converts audio to mel-spectrogram images
- Emotion detected using CNN classifiers

#### CNN + LSTM Hybrid

- Captures both spatial (frequency) and temporal (time) features

---

💡 **Tip**: Use both text and audio pipelines in parallel for improved emotion detection in call center or real-time dialogue systems.



