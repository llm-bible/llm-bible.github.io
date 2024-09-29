---
layout: publication
title: Data Augmentation for Neural Machine Translation using Generative Language Model
authors: Oh Seokjin, Lee Su Ah, Jung Woohwan
conference: "Arxiv"
year: 2023
bibkey: oh2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.16833"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Despite the rapid growth in model architecture the scarcity of large parallel corpora remains the main bottleneck in Neural Machine Translation. Data augmentation is a technique that enhances the performance of data-hungry models by generating synthetic data instead of collecting new ones. We explore prompt-based data augmentation approaches that leverage large-scale language models such as ChatGPT. To create a synthetic parallel corpus we compare 3 methods using different prompts. We employ two assessment metrics to measure the diversity of the generated synthetic data. This approach requires no further model training cost which is mandatory in other augmentation methods like back-translation. The proposed method improves the unaugmented baseline by 0.68 BLEU score.
