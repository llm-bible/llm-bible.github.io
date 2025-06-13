---
layout: publication
title: 'Teach2eval: An Indirect Evaluation Method For LLM By Judging How It Teaches'
authors: Yuhang Zhou, Xutian Chen, Yixin Cao, Yuchen Ni, Yu He, Siyu Tian, Xiang Liu, Jian Zhang, Chuanjun Ji, Guangnan Ye, Xipeng Qiu
conference: "Arxiv"
year: 2025
bibkey: zhou2025indirect
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12259"}
tags: ['Training Techniques', 'Fairness', 'Tools', 'Bias Mitigation', 'Ethics and Bias', 'Interpretability and Explainability']
---
Recent progress in large language models (LLMs) has outpaced the development of effective evaluation methods. Traditional benchmarks rely on task-specific metrics and static datasets, which often suffer from fairness issues, limited scalability, and contamination risks. In this paper, we introduce Teach2Eval, an indirect evaluation framework inspired by the Feynman Technique. Instead of directly testing LLMs on predefined tasks, our method evaluates a model's multiple abilities to teach weaker student models to perform tasks effectively. By converting open-ended tasks into standardized multiple-choice questions (MCQs) through teacher-generated feedback, Teach2Eval enables scalable, automated, and multi-dimensional assessment. Our approach not only avoids data leakage and memorization but also captures a broad range of cognitive abilities that are orthogonal to current benchmarks. Experimental results across 26 leading LLMs show strong alignment with existing human and model-based dynamic rankings, while offering additional interpretability for training guidance.
