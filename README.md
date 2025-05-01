# mistral-to-roberta
Train a smaller student model using soft labels (probabilities) from a larger teacher model, rather than hard labels.

# Tweet Distillation: Mistral → RoBERTa

This repository presents a lightweight tweet language model distilled from the powerful Mistral model into a compact RoBERTa-based student. The goal is to retain performance on short-form Tamil content (like tweets) while reducing model size and improving inference speed.

## 🔍 Project Objective

- Use **knowledge distillation** to train a compact **RoBERTa** model using **Mistral** as the teacher.
- Fine-tune both teacher and student on **tweet datasets**.
- Optimize for performance on classification and understanding tasks (e.g., sentiment analysis).

## 🧠 Model Overview

- **Teacher Model**: [Mistral-7B](https://huggingface.co/mistralai/Mistral-7B-v0.1)
- **Student Model**: A distilled variant of [RoBERTa](https://huggingface.co/roberta-base) fine-tuned on Tamil tweet data



