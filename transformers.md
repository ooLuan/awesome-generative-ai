# 🤖 Transformers & Foundation Models

A curated collection of widely-used transformer models across NLP, multimodal, and large language model (LLM) domains.

---

## 📚 Natural Language Transformers

### 🔹 [BERT (Bidirectional Encoder Representations from Transformers)](https://github.com/google-research/bert)
- Pretrained on masked language modeling and next sentence prediction
- Foundation for many downstream NLP tasks

### 🔹 [RoBERTa](https://github.com/pytorch/fairseq/tree/main/examples/roberta)
- Robustly optimized BERT variant by Facebook AI
- Trained longer, with more data and no NSP objective

### 🔹 [ELECTRA](https://github.com/google-research/electra)
- More efficient pretraining via replaced token detection
- Outperforms BERT on many tasks with fewer compute

### 🔹 [KoBERT](https://github.com/SKTBrain/KoBERT)
- Korean BERT pretrained with Subword embeddings
- Optimized for downstream Korean NLP tasks

### 🔹 [DistilBERT](https://github.com/huggingface/transformers)
- A distilled version of BERT that is 60% faster and smaller

---

## 🧠 Large Language Models (LLMs)

### 🔹 [GPT-2 & GPT-3 (OpenAI)](https://platform.openai.com/docs)
- Autoregressive transformer models for text generation
- API-based usage for chat, summarization, QA, etc.

### 🔹 [LLaMA (Meta)](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)
- Open-weight LLMs with competitive performance
- LLaMA 2 and 3 available for research and commercial use

### 🔹 [Mistral](https://mistral.ai/news/announcing-mistral-7b/)
- Lightweight open-weight models (Mistral 7B)
- State-of-the-art on many benchmarks with low latency

### 🔹 [Falcon (TII)](https://huggingface.co/tiiuae/falcon-40b)
- 7B / 40B parameter LLMs for multilingual generation
- Ranked high in Open LLM Leaderboards

### 🔹 [Claude (Anthropic)](https://www.anthropic.com/index/introducing-claude)
- Alignment-first LLMs with long context window
- Claude 3 supports structured tool use and reasoning

### 🔹 [Gemini (Google DeepMind)](https://ai.google.dev/gemini-api/docs)
- Multimodal LLM supporting vision, audio, and code inputs
- Combines capabilities of PaLM + DeepMind Alpha

---

## 🖼️ Vision & Multimodal Transformers

### 🔹 [ViT (Vision Transformer)](https://github.com/google-research/vision_transformer)
- Pure transformer architecture for image classification

### 🔹 [BLIP-2](https://github.com/salesforce/BLIP)
- Vision-language pretraining for image captioning and VQA

### 🔹 [FLAN-T5](https://huggingface.co/google/flan-t5-xxl)
- Instruction-tuned T5 model by Google
- Works well for prompt-based inference tasks

---

💡 **Tip**: Use HuggingFace Transformers library for seamless loading and fine-tuning of these models.


