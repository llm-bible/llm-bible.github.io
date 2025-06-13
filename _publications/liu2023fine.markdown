---
layout: publication
title: 'Goat: Fine-tuned Llama Outperforms GPT-4 On Arithmetic Tasks'
authors: Tiedong Liu, Bryan Kian Hsiang Low
conference: "Arxiv"
year: 2023
bibkey: liu2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14201"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'Few-Shot']
---
We introduce Goat, a fine-tuned LLaMA model that significantly outperforms
GPT-4 on a range of arithmetic tasks. Fine-tuned on a synthetically generated
dataset, Goat achieves state-of-the-art performance on BIG-bench arithmetic
sub-task. In particular, the zero-shot Goat-7B matches or even surpasses the
accuracy achieved by the few-shot PaLM-540B. Surprisingly, Goat can achieve
near-perfect accuracy on large-number addition and subtraction through
supervised fine-tuning only, which is almost impossible with previous
pretrained language models, such as Bloom, OPT, GPT-NeoX, etc. We attribute
Goat's exceptional performance to LLaMA's consistent tokenization of numbers.
To tackle more challenging tasks like large-number multiplication and division,
we propose an approach that classifies tasks based on their learnability, and
subsequently decomposes unlearnable tasks, such as multi-digit multiplication
and division, into a series of learnable tasks by leveraging basic arithmetic
principles. We thoroughly examine the performance of our model, offering a
comprehensive evaluation of the effectiveness of our proposed decomposition
steps. Additionally, Goat-7B can be easily trained using LoRA on a 24GB VRAM
GPU, facilitating reproducibility for other researchers. We release our model,
dataset, and the Python script for dataset generation.
