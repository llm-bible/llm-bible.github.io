---
layout: publication
title: 'The N+ Implementation Details Of RLHF With PPO: A Case Study On TL;DR Summarization'
authors: Shengyi Huang, Michael Noukhovitch, Arian Hosseini, Kashif Rasul, Weixun Wang, Lewis Tunstall
conference: "Arxiv"
year: 2024
bibkey: huang2024implementation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17031"}
  - {name: "Code", url: "https://github.com/vwxyzjn/summarize_from_feedback_details})"}
tags: ['Agentic', 'Applications', 'Has Code', 'Reinforcement Learning']
---
This work is the first to openly reproduce the Reinforcement Learning from
Human Feedback (RLHF) scaling behaviors reported in OpenAI's seminal TL;DR
summarization work. We create an RLHF pipeline from scratch, enumerate over 20
key implementation details, and share key insights during the reproduction. Our
RLHF-trained Pythia models demonstrate significant gains in response quality
that scale with model size, with our 2.8B, 6.9B models outperforming OpenAI's
released 1.3B checkpoint. We publicly release the trained model checkpoints and
code to facilitate further research and accelerate progress in the field
(\url\{https://github.com/vwxyzjn/summarize_from_feedback_details\}).
