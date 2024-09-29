---
layout: publication
title: Token45;picker Accelerating Attention In Text Generation With Minimized Memory Transfer Via Probability Estimation
authors: Park Junyoung, Kang Myeonggu, Han Yunki, Kim Yanggon, Shin Jaekang, Kim Lee-sup
conference: "Arxiv"
year: 2024
bibkey: park2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15131"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pruning', 'RAG', 'Reinforcement Learning', 'Transformer']
---
The attention mechanism in text generation is memory45;bounded due to its sequential characteristics. Therefore off45;chip memory accesses should be minimized for faster execution. Although previous methods addressed this by pruning unimportant tokens they fall short in selectively removing tokens with near45;zero attention probabilities in each instance. Our method estimates the probability before the softmax function effectively removing low probability tokens and achieving an 12.1x pruning ratio without fine45;tuning. Additionally we present a hardware design supporting seamless on45;demand off45;chip access. Our approach shows 2.6x reduced memory accesses leading to an average 2.3x speedup and a 2.4x energy efficiency.
