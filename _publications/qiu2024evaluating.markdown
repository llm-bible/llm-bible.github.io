---
layout: publication
title: 'Evaluating Cultural And Social Awareness Of LLM Web Agents'
authors: Haoyi Qiu, Alexander R. Fabbri, Divyansh Agarwal, Kung-hsiang Huang, Sarah Tan, Nanyun Peng, Chien-sheng Wu
conference: "Arxiv"
year: 2024
bibkey: qiu2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23252'}
tags: ['Agentic', 'RAG', 'Security', 'Applications', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
As large language models (LLMs) expand into performing as agents for
real-world applications beyond traditional NLP tasks, evaluating their
robustness becomes increasingly important. However, existing benchmarks often
overlook critical dimensions like cultural and social awareness. To address
these, we introduce CASA, a benchmark designed to assess LLM agents'
sensitivity to cultural and social norms across two web-based tasks: online
shopping and social discussion forums. Our approach evaluates LLM agents'
ability to detect and appropriately respond to norm-violating user queries and
observations. Furthermore, we propose a comprehensive evaluation framework that
measures awareness coverage, helpfulness in managing user queries, and the
violation rate when facing misleading web content. Experiments show that
current LLMs perform significantly better in non-agent than in web-based agent
environments, with agents achieving less than 10% awareness coverage and over
40% violation rates. To improve performance, we explore two methods: prompting
and fine-tuning, and find that combining both methods can offer complementary
advantages -- fine-tuning on culture-specific datasets significantly enhances
the agents' ability to generalize across different regions, while prompting
boosts the agents' ability to navigate complex tasks. These findings highlight
the importance of constantly benchmarking LLM agents' cultural and social
awareness during the development cycle.
