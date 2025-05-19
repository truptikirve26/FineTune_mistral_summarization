# 🧠 Fine-Tuning Mistral-7B with QLoRA on SAMSum 📄➡️🧾

This project demonstrates how to fine-tune the [Mistral-7B](https://huggingface.co/mistralai/Mistral-7B-v0.1) model on the SAMSum dataset for dialogue summarization using **QLoRA** — a memory-efficient method for adapting large language models using low-rank adapters and 4-bit quantization.

---

## 🔍 What You'll Learn

- ✅ How to load and preprocess the `samsum` dataset
- ✅ How to quantize a large model using `bitsandbytes`
- ✅ How to apply **QLoRA** (4-bit + Low-Rank Adaptation)
- ✅ How to train the model using Hugging Face's `SFTTrainer`
- ✅ How to evaluate and run sample summarizations

## 🛠️ Environment Setup

### 1. Ensure GPU Access (Required)
This tutorial **requires a CUDA-enabled GPU**. Check your setup:

```bash
nvidia-smi


