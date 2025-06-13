---
layout: publication
title: 'Investigating Recent Large Language Models For Vietnamese Machine Reading Comprehension'
authors: Anh Duc Nguyen, Hieu Minh Phi, Anh Viet Ngo, Long Hai Trieu, Thai Phuong Nguyen
conference: "Arxiv"
year: 2025
bibkey: nguyen2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18062"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Large Language Models (LLMs) have shown remarkable proficiency in Machine
Reading Comprehension (MRC) tasks; however, their effectiveness for
low-resource languages like Vietnamese remains largely unexplored. In this
paper, we fine-tune and evaluate two state-of-the-art LLMs: Llama 3 (8B
parameters) and Gemma (7B parameters), on ViMMRC, a Vietnamese MRC dataset. By
utilizing Quantized Low-Rank Adaptation (QLoRA), we efficiently fine-tune these
models and compare their performance against powerful LLM-based baselines.
Although our fine-tuned models are smaller than GPT-3 and GPT-3.5, they
outperform both traditional BERT-based approaches and these larger models. This
demonstrates the effectiveness of our fine-tuning process, showcasing how
modern LLMs can surpass the capabilities of older models like BERT while still
being suitable for deployment in resource-constrained environments. Through
intensive analyses, we explore various aspects of model performance, providing
valuable insights into adapting LLMs for low-resource languages like
Vietnamese. Our study contributes to the advancement of natural language
processing in low-resource languages, and we make our fine-tuned models
publicly available at: https://huggingface.co/iaiuet.
