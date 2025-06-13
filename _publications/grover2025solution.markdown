---
layout: publication
title: 'Finrllama: A Solution To Llm-engineered Signals Challenge At Finrl Contest 2024'
authors: Arnav Grover
conference: "Arxiv"
year: 2025
bibkey: grover2025solution
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01992'}
tags: ['Agentic', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
In response to Task II of the FinRL Challenge at ACM ICAIF 2024, this study
proposes a novel prompt framework for fine-tuning large language models (LLM)
with Reinforcement Learning from Market Feedback (RLMF). Our framework
incorporates market-specific features and short-term price dynamics to generate
more precise trading signals. Traditional LLMs, while competent in sentiment
analysis, lack contextual alignment for financial market applications. To
bridge this gap, we fine-tune the LLaMA-3.2-3B-Instruct model using a custom
RLMF prompt design that integrates historical market data and reward-based
feedback. Our evaluation shows that this RLMF-tuned framework outperforms
baseline methods in signal consistency and achieving tighter trading outcomes;
awarded as winner of Task II. You can find the code for this project on GitHub.
