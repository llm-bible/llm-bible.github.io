---
layout: publication
title: 'Finetune-rag: Fine-tuning Language Models To Resist Hallucination In Retrieval-augmented Generation'
authors: Zhan Peng Lee, Andre Lin, Calvin Tan
conference: "Arxiv"
year: 2025
bibkey: lee2025finetune
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10792'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Retrieval-Augmented Generation (RAG) has emerged as a powerful framework to improve factuality in large language models (LLMs) by grounding their outputs in retrieved documents. However, ensuring perfect retrieval of relevant information remains challenging, and when irrelevant content is passed downstream to an LLM, it can lead to hallucinations. In this work, we propose Finetune-RAG, a simple and effective fine-tuning approach that features the first-of-its-kind RAG training dataset constructed to mimic real-world imperfections. Experimental results show that Finetune-RAG improves factual accuracy by 21.2% over the base model. We also propose Bench-RAG, an LLM-as-a-judge evaluation pipeline that stress tests models under realistic imperfect retrieval scenarios. Our codebase and dataset are fully open sourced for community use.
