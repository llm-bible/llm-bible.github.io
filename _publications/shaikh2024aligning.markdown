---
layout: publication
title: 'Show, Don''t Tell: Aligning Language Models With Demonstrated Feedback'
authors: Shaikh Omar, Lam Michelle, Hejna Joey, Shao Yijia, Bernstein Michael, Yang Diyi
conference: "Arxiv"
year: 2024
bibkey: shaikh2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00888"}
tags: ['Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
"Language models are aligned to emulate the collective voice of many, resulting in outputs that align with no one in particular. Steering LLMs away from generic output is possible through supervised finetuning or RLHF, but requires prohibitively large datasets for new ad-hoc tasks. We argue that it is instead possible to align an LLM to a specific setting by leveraging a very small number (\(<10\)) of demonstrations as feedback. Our method, Demonstration ITerated Task Optimization (DITTO), directly aligns language model outputs to a user's demonstrated behaviors. Derived using ideas from online imitation learning, DITTO cheaply generates online comparison data by treating users' demonstrations as preferred over output from the LLM and its intermediate checkpoints. We evaluate DITTO's ability to learn fine-grained style and task alignment across domains such as news articles, emails, and blog posts. Additionally, we conduct a user study soliciting a range of demonstrations from participants (\(N=16\)). Across our benchmarks and user study, we find that win-rates for DITTO outperform few-shot prompting, supervised fine-tuning, and other self-play methods by an average of 19&#37; points. By using demonstrations as feedback directly, DITTO offers a novel method for effective customization of LLMs."
