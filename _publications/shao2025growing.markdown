---
layout: publication
title: 'Growing A Twig To Accelerate Large Vision-language Models'
authors: Zhenwei Shao, Mingyang Wang, Zhou Yu, Wenwen Pan, Yan Yang, Tao Wei, Hongyuan Zhang, Ning Mao, Wei Chen, Jun Yu
conference: "Arxiv"
year: 2025
bibkey: shao2025growing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14075"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Pruning', 'Attention Mechanism']
---
Large vision-language models (VLMs) have demonstrated remarkable capabilities
in open-world multimodal understanding, yet their high computational overheads
pose great challenges for practical deployment. Some recent works have proposed
methods to accelerate VLMs by pruning redundant visual tokens guided by the
attention maps of VLM's early layers. Despite the success of these token
pruning methods, they still suffer from two major shortcomings: (i)
considerable accuracy drop due to insensitive attention signals in early
layers, and (ii) limited speedup when generating long responses (e.g., 30
tokens). To address the limitations above, we present TwigVLM -- a simple and
general architecture by growing a lightweight twig upon an early layer of the
base VLM. Compared with most existing VLM acceleration methods purely based on
visual token pruning, our TwigVLM not only achieves better accuracy retention
by employing a twig-guided token pruning (TTP) strategy, but also yields higher
generation speed by utilizing a self-speculative decoding (SSD) strategy.
Taking LLaVA-1.5-7B as the base VLM, experimental results show that TwigVLM
preserves 96% of the original performance after pruning 88.9% of visual tokens
and achieves 154% speedup in generating long responses, delivering
significantly better performance in terms of both accuracy and speed over the
state-of-the-art VLM acceleration methods. Code will be made publicly
available.
