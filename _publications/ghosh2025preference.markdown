---
layout: publication
title: 'Preference VLM: Leveraging Vlms For Scalable Preference-based Reinforcement Learning'
authors: Udita Ghosh, Dripta S. Raychaudhuri, Jiachen Li, Konstantinos Karydis, Amit Roy-chowdhury
conference: "Arxiv"
year: 2025
bibkey: ghosh2025preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01616"}
tags: ['Agentic', 'Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
Preference-based reinforcement learning (RL) offers a promising approach for
aligning policies with human intent but is often constrained by the high cost
of human feedback. In this work, we introduce PrefVLM, a framework that
integrates Vision-Language Models (VLMs) with selective human feedback to
significantly reduce annotation requirements while maintaining performance. Our
method leverages VLMs to generate initial preference labels, which are then
filtered to identify uncertain cases for targeted human annotation.
Additionally, we adapt VLMs using a self-supervised inverse dynamics loss to
improve alignment with evolving policies. Experiments on Meta-World
manipulation tasks demonstrate that PrefVLM achieves comparable or superior
success rates to state-of-the-art methods while using up to 2 x fewer human
annotations. Furthermore, we show that adapted VLMs enable efficient knowledge
transfer across tasks, further minimizing feedback needs. Our results highlight
the potential of combining VLMs with selective human supervision to make
preference-based RL more scalable and practical.
