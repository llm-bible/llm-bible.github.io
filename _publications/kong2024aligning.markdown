---
layout: publication
title: 'Aligning Large Language Models With Representation Editing: A Control Perspective'
authors: Lingkai Kong, Haorui Wang, Wenhao Mu, Yuanqi Du, Yuchen Zhuang, Yifei Zhou, Yue Song, Rongzhi Zhang, Kai Wang, Chao Zhang
conference: "Arxiv"
year: 2024
bibkey: kong2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05954"}
  - {name: "Code", url: "https://github.com/Lingkai-Kong/RE-Control"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Aligning large language models (LLMs) with human objectives is crucial for
real-world applications. However, fine-tuning LLMs for alignment often suffers
from unstable training and requires substantial computing resources. Test-time
alignment techniques, such as prompting and guided decoding, do not modify the
underlying model, and their performance remains dependent on the original
model's capabilities. To address these challenges, we propose aligning LLMs
through representation editing. The core of our method is to view a pre-trained
autoregressive LLM as a discrete-time stochastic dynamical system. To achieve
alignment for specific objectives, we introduce external control signals into
the state space of this language dynamical system. We train a value function
directly on the hidden states according to the Bellman equation, enabling
gradient-based optimization to obtain the optimal control signals at test time.
Our experiments demonstrate that our method outperforms existing test-time
alignment techniques while requiring significantly fewer resources compared to
fine-tuning methods. Our code is available at
https://github.com/Lingkai-Kong/RE-Control.
