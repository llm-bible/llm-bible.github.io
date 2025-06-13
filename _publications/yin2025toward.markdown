---
layout: publication
title: 'Toward Scientific Reasoning In Llms: Training From Expert Discussions Via Reinforcement Learning'
authors: Ming Yin, Yuanhao Qu, Ling Yang, Le Cong, Mengdi Wang
conference: "Arxiv"
year: 2025
bibkey: yin2025toward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19501'}
tags: ['Reinforcement Learning', 'RAG', 'Agentic', 'Training Techniques']
---
We investigate how to teach large language models (LLMs) to perform scientific reasoning by leveraging expert discussions as a learning signal. Focusing on the genomics domain, we develop an automated pipeline to extract trainable data and introduce Genome-Bench, a new benchmark constructed from over a decade of scientific forum discussions on genome engineering. Our pipeline transforms raw interactions into a reinforcement learning-friendly multiple-choice questions format, supported by 3000+ high-quality question-answer pairs spanning foundational biology, experimental troubleshooting, tool usage, and beyond. We fine-tune an LLM using RL with a rule-based reward signal derived from the synthetic MCQ dataset to enhance domain-specific reasoning. Our results show that reinforcement learning from scientific discussions improves model performance by over 15% compared to the base model on Genome-Bench, narrowing the gap between open-source LLMs and expert-level reasoning. To our knowledge, this is the first end-to-end pipeline for teaching LLMs to reason from scientific discussions, with promising potential for generalization across scientific domains beyond biology.
