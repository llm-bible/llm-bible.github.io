---
layout: publication
title: 'Moba: Mixture Of Block Attention For Long-context Llms'
authors: Enzhe Lu, Zhejun Jiang, Jingyuan Liu, Yulun Du, Tao Jiang, Chao Hong, Shaowei Liu, Weiran He, Enming Yuan, Yuzhi Wang, Zhiqi Huang, Huan Yuan, Suting Xu, Xinran Xu, Guokun Lai, Yanru Chen, Huabin Zheng, Junjie Yan, Jianlin Su, Yuxin Wu, Neo Y. Zhang, Zhilin Yang, Xinyu Zhou, Mingxing Zhang, Jiezhong Qiu
conference: "Arxiv"
year: 2025
bibkey: lu2025mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13189'}
  - {name: "Code", url: 'https://github.com/MoonshotAI/MoBA'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias']
---
Scaling the effective context length is essential for advancing large
language models (LLMs) toward artificial general intelligence (AGI). However,
the quadratic increase in computational complexity inherent in traditional
attention mechanisms presents a prohibitive overhead. Existing approaches
either impose strongly biased structures, such as sink or window attention
which are task-specific, or radically modify the attention mechanism into
linear approximations, whose performance in complex reasoning tasks remains
inadequately explored.
  In this work, we propose a solution that adheres to the ``less structure''
principle, allowing the model to determine where to attend autonomously, rather
than introducing predefined biases. We introduce Mixture of Block Attention
(MoBA), an innovative approach that applies the principles of Mixture of
Experts (MoE) to the attention mechanism. This novel architecture demonstrates
superior performance on long-context tasks while offering a key advantage: the
ability to seamlessly transition between full and sparse attention, enhancing
efficiency without the risk of compromising performance. MoBA has already been
deployed to support Kimi's long-context requests and demonstrates significant
advancements in efficient attention computation for LLMs. Our code is available
at https://github.com/MoonshotAI/MoBA.
