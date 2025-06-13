---
layout: publication
title: 'JARVIS-VLA: Post-training Large-scale Vision Language Models To Play Visual Games With Keyboards And Mouse'
authors: Muyao Li, Zihao Wang, Kaichen He, Xiaojian Ma, Yitao Liang
conference: "Arxiv"
year: 2025
bibkey: li2025jarvis
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16365'}
  - {name: "Code", url: 'https://craftjarvis.github.io/JarvisVLA'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning']
---
Recently, action-based decision-making in open-world environments has gained
significant attention. Visual Language Action (VLA) models, pretrained on
large-scale web datasets, have shown promise in decision-making tasks. However,
previous work has primarily focused on action post-training, often neglecting
enhancements to the foundational model itself. In response, we introduce a
novel approach, Act from Visual Language Post-Training, which refines Visual
Language Models (VLMs) through visual and linguistic guidance in a
self-supervised manner. This enhancement improves the models' capabilities in
world knowledge, visual recognition, and spatial grounding in open-world
environments. Following the above post-training paradigms, we obtain the first
VLA models in Minecraft that can follow human instructions on over 1k different
atomic tasks, including crafting, smelting, cooking, mining, and killing. Our
experiments demonstrate that post-training on non-trajectory tasks leads to a
significant 40% improvement over the best agent baseline on a diverse set of
atomic tasks. Furthermore, we demonstrate that our approach surpasses
traditional imitation learning-based policies in Minecraft, achieving
state-of-the-art performance. We have open-sourced the code, models, and
datasets to foster further research. The project page can be found in
https://craftjarvis.github.io/JarvisVLA.
