# LLMs From Scratch

This repository contains implementations of LLMs built from scratch using PyTorch.

## Projects

### PaliGemma VLM from Scratch

An implementation of Google's PaliGemma Vision-Language Model, built from scratch following Umar Jamil's [tutorial](https://www.youtube.com/watch?v=vAmKB7iPkWw).

**Details:**
- Integrated SigLIP vision encoder with Gemma language model using PyTorch
- Reimplemented core components including SwiGLU activation, multi-head self-attention with causal masking, and KV-caching
- Built processing pipeline for handling vision-text multimodal inputs

### GPT-2 from Scratch

A reimplementation of OpenAI's GPT-2 following Sebastian Raschka's [book](https://www.manning.com/books/build-a-large-language-model-from-scratch) "Build a Large Language Model (From Scratch)".

**Details:**
- Implemented custom tokenizer, attention mechanisms, feedforward networks, and complete training pipeline
- Fine-tuned model for text classification tasks
