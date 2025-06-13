---
layout: publication
title: 'Can Large Language Models Generate High-quality Patent Claims?'
authors: Lekang Jiang, Caiqi Zhang, Pascal A Scherz, Stephan Goetz
conference: "Findings of the Association for Computational Linguistics NAACL 2025 pages 1272-1287"
year: 2024
bibkey: jiang2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19465"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Language Modeling', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have shown exceptional performance across various text generation tasks but remain under-explored in the patent domain, which offers highly structured and precise language. This paper constructs a dataset to investigate the performance of current LLMs in patent claim generation. Our results demonstrate that generating claims based on patent descriptions outperforms previous research relying on abstracts. Interestingly, current patent-specific LLMs perform much worse than state-of-the-art general LLMs, highlighting the necessity for future research on in-domain LLMs. We also find that LLMs can produce high-quality first independent claims, but their performances markedly decrease for subsequent dependent claims. Moreover, fine-tuning can enhance the completeness of inventions' features, conceptual clarity, and feature linkage. Among the tested LLMs, GPT-4 demonstrates the best performance in comprehensive human evaluations by patent experts, with better feature coverage, conceptual clarity, and technical coherence. Despite these capabilities, comprehensive revision and modification are still necessary to pass rigorous patent scrutiny and ensure legal robustness.
