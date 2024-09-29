---
layout: publication
title: Chat-3D Data-efficiently Tuning Large Language Model for Universal Dialogue of 3D Scenes
authors: Wang Zehan, Huang Haifeng, Zhao Yang, Zhang Ziang, Zhao Zhou
conference: "Arxiv"
year: 2023
bibkey: wang2023chat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.08769"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
3D scene understanding has gained significant attention due to its wide range of applications. However existing methods for 3D scene understanding are limited to specific downstream tasks which hinders their practicality in real-world applications. This paper presents Chat-3D which combines the 3D visual perceptual ability of pre-trained 3D representations and the impressive reasoning and conversation capabilities of advanced LLMs to achieve the first universal dialogue systems for 3D scenes. Specifically we align 3D representations into the feature space of LLMs thus enabling LLMs to perceive the 3D world. Given the scarcity of 3D scene-text data we propose a three-stage training strategy to efficiently utilize the available data for better alignment. To enhance the reasoning ability and develop a user-friendly interaction scheme we further construct a high-quality object-centric 3D instruction dataset and design an associated object-centric prompt. Our experiments show that Chat-3D achieves an impressive ability to comprehend diverse instructions for 3D scenes engage in intricate spatial reasoning and incorporate external knowledge into its responses. Chat-3D achieves a 75.6 relative score compared with GPT-4 on the constructed instruction dataset.
