---
layout: publication
title: 'Effective Text Adaptation For Llm-based ASR Through Soft Prompt Fine-tuning'
authors: Yingyi Ma, Zhe Liu, Ozlem Kalinli
conference: "Arxiv"
year: 2024
bibkey: ma2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06967"}
tags: ['Fine-Tuning', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
The advent of Large Language Models (LLM) has reformed the Automatic Speech
Recognition (ASR). Prompting LLM with audio embeddings to generate
transcriptions becomes the new state-of-the-art ASR. Despite LLMs being trained
with an extensive amount of text corpora, high-quality domain-specific text
data can still significantly enhance ASR performance on domain adaptation
tasks. Although LLM-based ASR can naturally incorporate more text corpora by
fine-tuning the LLM decoder, fine-tuning such ASR on text-only data without
paired prompts may diminish the effectiveness of domain-specific knowledge. To
mitigate this issue, we propose a two-step soft prompt fine-tuning strategy
that enhances domain-specific text adaptation. Experimental results show that
text adaptation with our proposed method achieved a relative up to 9% Word
Error Rate (WER) reduction and up to 18% Entity Error Rate (EER) reduction on
the target domain compared to the baseline ASR. Combining this with
domain-specific Language Model (LM) fusion can further improve the EER by a
relative 2-5%
