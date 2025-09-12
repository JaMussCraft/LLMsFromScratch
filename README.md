# Large Language Models From Scratch

This repository contains two comprehensive implementations of state-of-the-art language models built entirely from scratch using PyTorch. Each project demonstrates deep understanding of transformer architectures, attention mechanisms, and modern AI techniques.

## Projects

### 🔍 PaliGemma VLM from Scratch

A complete implementation of Google's PaliGemma Vision-Language Model, built from the ground up following Umar Jamil's comprehensive tutorial.

**Technical Implementation:**
- Built multimodal transformer from scratch, integrating SigLIP vision encoder with Gemma language model using PyTorch
- Reimplemented core components including SwiGLU activation, multi-head self-attention with causal masking, and KV-caching for efficient inference
- Developed custom processing pipeline for handling vision-text multimodal inputs

**Resources:**
- 📺 [YouTube Tutorial](https://www.youtube.com/watch?v=vAmKB7iPkWw) by Umar Jamil
- 🔗 [Reference Implementation](https://github.com/hkproj/pytorch-paligemma)

### 🤖 GPT-2 FROM SCRATCH

A faithful reproduction of OpenAI's GPT-2 architecture, implemented while following Sebastian Raschka's book "Build a Large Language Model (From Scratch)".

**Technical Implementation:**
- Implemented GPT-2 from scratch with custom tokenizer, attention mechanisms, feedforward networks, and complete training pipeline
- Explored architectural variants including separate vs. combined QKV attention mechanisms
- Fine-tuned model for text classification tasks, demonstrating transfer learning capabilities
- Built comprehensive training infrastructure with proper data loading, optimization, and evaluation

**Key Components:**
- Custom tokenizer implementation
- Multi-head self-attention with causal masking
- Position embeddings and layer normalization
- Training pipeline with gradient accumulation
- Model evaluation and text generation

## Repository Structure

```
├── paligemma/          # PaliGemma VLM implementation
│   ├── modeling_gemma.py      # Gemma language model
│   ├── modeling_siglip.py     # SigLIP vision encoder
│   └── processing_paligemma.py # Multimodal processing
└── gpt_2/              # GPT-2 implementation by chapters
    ├── chapter2/       # Basic attention mechanisms
    ├── chapter3/       # Multi-head attention
    ├── chapter4/       # GPT model implementation
    ├── chapter5/       # Training pipeline
    └── chapter6/       # Fine-tuning and classification
```

## Skills Demonstrated

- **Deep Learning Architecture Design**: Implementation of transformer models from mathematical foundations
- **PyTorch Expertise**: Advanced usage of PyTorch for custom model development
- **Computer Vision**: Integration of vision encoders with language models
- **Natural Language Processing**: Tokenization, attention mechanisms, and language modeling
- **Model Training**: End-to-end training pipelines, optimization, and fine-tuning
- **Code Organization**: Clean, modular code structure following best practices
