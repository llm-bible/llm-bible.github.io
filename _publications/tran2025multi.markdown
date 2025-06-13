---
layout: publication
title: 'Irlbench: A Multi-modal, Culturally Grounded, Parallel Irish-english Benchmark For Open-ended LLM Reasoning Evaluation'
authors: Khanh-tung Tran, Barry O'sullivan, Hoang D. Nguyen
conference: "Arxiv"
year: 2025
bibkey: tran2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13498"}
  - {name: "Code", url: "https://huggingface.co/datasets/ReliableAI/IRLBench)"}
  - {name: "Code", url: "https://github.com/ReML-AI/IRLBench)"}
tags: ['RAG', 'Has Code', 'Ethics and Bias', 'Reinforcement Learning']
---
Recent advances in Large Language Models (LLMs) have demonstrated promising knowledge and reasoning abilities, yet their performance in multilingual and low-resource settings remains underexplored. Existing benchmarks often exhibit cultural bias, restrict evaluation to text-only, rely on multiple-choice formats, and, more importantly, are limited for extremely low-resource languages. To address these gaps, we introduce IRLBench, presented in parallel English and Irish, which is considered definitely endangered by UNESCO. Our benchmark consists of 12 representative subjects developed from the 2024 Irish Leaving Certificate exams, enabling fine-grained analysis of model capabilities across domains. By framing the task as long-form generation and leveraging the official marking scheme, it does not only support a comprehensive evaluation of correctness but also language fidelity. Our extensive experiments of leading closed-source and open-source LLMs reveal a persistent performance gap between English and Irish, in which models produce valid Irish responses less than 80% of the time, and answer correctly 55.8% of the time compared to 76.2% in English for the best-performing model. We release IRLBench (https://huggingface.co/datasets/ReliableAI/IRLBench) and an accompanying evaluation codebase (https://github.com/ReML-AI/IRLBench) to enable future research on robust, culturally aware multilingual AI development.
