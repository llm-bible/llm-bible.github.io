---
layout: publication
title: 'Read Your Own Mind: Reasoning Helps Surface Self-confidence Signals In Llms'
authors: Jakub Podolak, Rajeev Verma
conference: "Arxiv"
year: 2025
bibkey: podolak2025read
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23845'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Applications']
---
We study the source of uncertainty in DeepSeek R1-32B by analyzing its self-reported verbal confidence on question answering (QA) tasks. In the default answer-then-confidence setting, the model is regularly over-confident, whereas semantic entropy - obtained by sampling many responses - remains reliable. We hypothesize that this is because of semantic entropy's larger test-time compute, which lets us explore the model's predictive distribution. We show that granting DeepSeek the budget to explore its distribution by forcing a long chain-of-thought before the final answer greatly improves its verbal score effectiveness, even on simple fact-retrieval questions that normally require no reasoning. Furthermore, a separate reader model that sees only the chain can reconstruct very similar confidences, indicating the verbal score might be merely a statistic of the alternatives surfaced during reasoning. Our analysis concludes that reliable uncertainty estimation requires explicit exploration of the generative space, and self-reported confidence is trustworthy only after such exploration.
