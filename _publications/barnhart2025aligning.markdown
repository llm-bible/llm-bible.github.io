---
layout: publication
title: 'Aligning To What? Limits To RLHF Based Alignment'
authors: Logan Barnhart, Reza Akbarian Bafghi, Stephen Becker, Maziar Raissi
conference: "Arxiv"
year: 2025
bibkey: barnhart2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.09025'}
tags: ['Agentic', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias']
---
Reinforcement Learning from Human Feedback (RLHF) is increasingly used to
align large language models (LLMs) with human preferences. However, the
effectiveness of RLHF in addressing underlying biases remains unclear. This
study investigates the relationship between RLHF and both covert and overt
biases in LLMs, particularly focusing on biases against African Americans. We
applied various RLHF techniques (DPO, ORPO, and RLOO) to Llama 3 8B and
evaluated the covert and overt biases of the resulting models using
matched-guise probing and explicit bias testing. We performed additional tests
with DPO on different base models and datasets; among several implications, we
found that SFT before RLHF calcifies model biases. Additionally, we extend the
tools for measuring biases to multi-modal models. Through our experiments we
collect evidence that indicates that current alignment techniques are
inadequate for nebulous tasks such as mitigating covert biases, highlighting
the need for capable datasets, data curating techniques, or alignment tools.
