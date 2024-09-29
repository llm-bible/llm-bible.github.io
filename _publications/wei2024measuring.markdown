---
layout: publication
title: Measuring And Reducing LLM Hallucination Without Gold-standard Answers
authors: Wei Jiaheng, Yao Yuanshun, Ton Jean-francois, Guo Hongyi, Estornell Andrew, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: wei2024measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10412"}
tags: ['Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
LLM hallucination i.e. generating factually incorrect yet seemingly convincing answers is currently a major threat to the trustworthiness and reliability of LLMs. The first step towards solving this complicated problem is to measure it. However existing hallucination metrics require having a benchmark dataset with gold-standard answers i.e. best or correct answers written by humans. Such requirements make hallucination measurement costly and prone to human errors. In this work we propose Factualness Evaluations via Weighting LLMs (FEWL) an innovative hallucination metric that is specifically designed for the scenario when gold-standard answers are absent. FEWL leverages the answers from off-the-shelf LLMs that serve as a proxy of gold-standard answers. The key challenge is how to quantify the expertise of reference LLMs resourcefully. We show FEWL has certain theoretical guarantees and demonstrate empirically it gives more accurate hallucination measures than naively using reference LLMs. We also show how to leverage FEWL to reduce hallucination through both in-context learning and supervised fine-tuning. Extensive experiment results on Truthful-QA CHALE and HaluEval datasets demonstrate the effectiveness of FEWL.
