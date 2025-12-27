---
title: "LLM Fine-Tuning with PEFT (LoRA)"
excerpt: "Parameter-efficient fine-tuning of large language models for domain adaptation and efficient deployment.<br/><img src='/images/llm_lora.png' alt='LLM LoRA' style='max-width:500px;height:auto;'>"
collection: portfolio
---

This project focuses on **adapting large language models using Parameter-Efficient Fine-Tuning (PEFT)** techniques, specifically **LoRA**, to specialize a pretrained LLM for a domain-specific task while keeping computational and memory costs low.

I implemented an end-to-end fine-tuning pipeline that includes dataset preparation, tokenizer alignment, LoRA-based adapter training, and evaluation of the adapted model.

**Key features:**
- Fine-tuning pretrained LLMs using **LoRA adapters**.
- Efficient training with frozen base weights to reduce GPU memory usage.
- Custom dataset preprocessing and prompt formatting.
- Evaluation of task performance before and after adaptation.
- Support for saving and reloading lightweight adapter weights.

**Tech stack:** Python, PyTorch, Hugging Face Transformers, PEFT, Datasets, Jupyter Notebook.

**Repository:** [GitHub - fine-tune-me-baby](https://github.com/PhenomSG/fine-tune-me-baby)

