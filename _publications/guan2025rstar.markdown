---
layout: publication
title: 'Rstar-math: Small Llms Can Master Math Reasoning With Self-evolved Deep Thinking'
authors: Xinyu Guan, Li Lyna Zhang, Yifei Liu, Ning Shang, Youran Sun, Yi Zhu, Fan Yang, Mao Yang
conference: "Arxiv"
year: 2025
bibkey: guan2025rstar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04519"}
  - {name: "Code", url: "https://github.com/microsoft/rStar"}
tags: ['Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Distillation']
---
We present rStar-Math to demonstrate that small language models (SLMs) can
rival or even surpass the math reasoning capability of OpenAI o1, without
distillation from superior models. rStar-Math achieves this by exercising "deep
thinking" through Monte Carlo Tree Search (MCTS), where a math policy SLM
performs test-time search guided by an SLM-based process reward model.
rStar-Math introduces three innovations to tackle the challenges in training
the two SLMs: (1) a novel code-augmented CoT data sythesis method, which
performs extensive MCTS rollouts to generate step-by-step verified reasoning
trajectories used to train the policy SLM; (2) a novel process reward model
training method that avoids na\"ive step-level score annotation, yielding a
more effective process preference model (PPM); (3) a self-evolution recipe in
which the policy SLM and PPM are built from scratch and iteratively evolved to
improve reasoning capabilities. Through 4 rounds of self-evolution with
millions of synthesized solutions for 747k math problems, rStar-Math boosts
SLMs' math reasoning to state-of-the-art levels. On the MATH benchmark, it
improves Qwen2.5-Math-7B from 58.8% to 90.0% and Phi3-mini-3.8B from 41.4% to
86.4%, surpassing o1-preview by +4.5% and +0.9%. On the USA Math Olympiad
(AIME), rStar-Math solves an average of 53.3% (8/15) of problems, ranking among
the top 20% the brightest high school math students. Code and data will be
available at https://github.com/microsoft/rStar.
