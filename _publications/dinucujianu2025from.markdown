---
layout: publication
title: 'From Problem-solving To Teaching Problem-solving: Aligning Llms With Pedagogy Using Reinforcement Learning'
authors: David Dinucu-jianu, Jakub Macina, Nico Daheim, Ido Hakimi, Iryna Gurevych, Mrinmaya Sachan
conference: "Arxiv"
year: 2025
bibkey: dinucujianu2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15607'}
tags: ['Agentic', 'Interpretability and Explainability', 'Efficiency and Optimization', 'Tools', 'Fine-Tuning', 'Reinforcement Learning']
---
Large language models (LLMs) can transform education, but their optimization for direct question-answering often undermines effective pedagogy which requires strategically withholding answers. To mitigate this, we propose an online reinforcement learning (RL)-based alignment framework that can quickly adapt LLMs into effective tutors using simulated student-tutor interactions by emphasizing pedagogical quality and guided problem-solving over simply giving away answers. We use our method to train a 7B parameter tutor model without human annotations which reaches similar performance to larger proprietary models like LearnLM. We introduce a controllable reward weighting to balance pedagogical support and student solving accuracy, allowing us to trace the Pareto frontier between these two objectives. Our models better preserve reasoning capabilities than single-turn SFT baselines and can optionally enhance interpretability through thinking tags that expose the model's instructional planning.
