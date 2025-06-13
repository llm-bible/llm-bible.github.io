---
layout: publication
title: 'Ld-scene: Llm-guided Diffusion For Controllable Generation Of Adversarial Safety-critical Driving Scenarios'
authors: Mingxing Peng, Yuting Xie, Xusen Guo, Ruoyu Yao, Hai Yang, Jun Ma
conference: "Arxiv"
year: 2025
bibkey: peng2025ld
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11247"}
tags: ['Responsible AI', 'Tools', 'Merging', 'Reinforcement Learning', 'Security']
---
Ensuring the safety and robustness of autonomous driving systems necessitates a comprehensive evaluation in safety-critical scenarios. However, these safety-critical scenarios are rare and difficult to collect from real-world driving data, posing significant challenges to effectively assessing the performance of autonomous vehicles. Typical existing methods often suffer from limited controllability and lack user-friendliness, as extensive expert knowledge is essentially required. To address these challenges, we propose LD-Scene, a novel framework that integrates Large Language Models (LLMs) with Latent Diffusion Models (LDMs) for user-controllable adversarial scenario generation through natural language. Our approach comprises an LDM that captures realistic driving trajectory distributions and an LLM-based guidance module that translates user queries into adversarial loss functions, facilitating the generation of scenarios aligned with user queries. The guidance module integrates an LLM-based Chain-of-Thought (CoT) code generator and an LLM-based code debugger, enhancing the controllability and robustness in generating guidance functions. Extensive experiments conducted on the nuScenes dataset demonstrate that LD-Scene achieves state-of-the-art performance in generating realistic, diverse, and effective adversarial scenarios. Furthermore, our framework provides fine-grained control over adversarial behaviors, thereby facilitating more effective testing tailored to specific driving scenarios.
