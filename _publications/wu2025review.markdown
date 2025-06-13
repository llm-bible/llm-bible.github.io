---
layout: publication
title: 'Review-instruct: A Review-driven Multi-turn Conversations Generation Method For Large Language Models'
authors: Jiangxu Wu, Cong Wang, Tianhuang Su, Jun Yang, Haozhi Lin, Chao Zhang, Ming Peng, Kai Shi, Songpan Yang, Binqing Pan, Zixian Li, Ni Yang, Zhenyu Yang
conference: "Arxiv"
year: 2025
bibkey: wu2025review
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11010"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Survey Paper', 'Training Techniques', 'Pretraining Methods']
---
The effectiveness of large language models (LLMs) in conversational AI is hindered by their reliance on single-turn supervised fine-tuning (SFT) data, which limits contextual coherence in multi-turn dialogues. Existing methods for generating multi-turn dialogue data struggle to ensure both diversity and quality in instructions. To address this, we propose Review-Instruct, a novel framework that synthesizes multi-turn conversations through an iterative "Ask-Respond-Review" process involving three agent roles: a Candidate, multiple Reviewers, and a Chairman. The framework iteratively refines instructions by incorporating Reviewer feedback, enhancing dialogue diversity and difficulty. We construct a multi-turn dataset using the Alpaca dataset and fine-tune the LLaMA2-13B model. Evaluations on MT-Bench, MMLU-Pro, and Auto-Arena demonstrate significant improvements, achieving absolute gains of 2.9% on MMLU-Pro and 2% on MT-Bench compared to prior state-of-the-art models based on LLaMA2-13B. Ablation studies confirm the critical role of the Review stage and the use of multiple Reviewers in boosting instruction diversity and difficulty. Our work highlights the potential of review-driven, multi-agent frameworks for generating high-quality conversational data at scale.
