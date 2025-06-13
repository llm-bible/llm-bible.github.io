---
layout: publication
title: '3UR-LLM: An End-to-end Multimodal Large Language Model For 3D Scene Understanding'
authors: Haomiao Xiong, Yunzhi Zhuge, Jiawen Zhu, Lu Zhang, Huchuan Lu
conference: "Arxiv"
year: 2025
bibkey: xiong2025end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.07819"}
tags: ['Pre-Training', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
Multi-modal Large Language Models (MLLMs) exhibit impressive capabilities in
2D tasks, yet encounter challenges in discerning the spatial positions,
interrelations, and causal logic in scenes when transitioning from 2D to 3D
representations. We find that the limitations mainly lie in: i) the high
annotation cost restricting the scale-up of volumes of 3D scene data, and ii)
the lack of a straightforward and effective way to perceive 3D information
which results in prolonged training durations and complicates the streamlined
framework. To this end, we develop pipeline based on open-source 2D MLLMs and
LLMs to generate high-quality 3D-text pairs and construct 3DS-160K , to enhance
the pre-training process. Leveraging this high-quality pre-training data, we
introduce the 3UR-LLM model, an end-to-end 3D MLLM designed for precise
interpretation of 3D scenes, showcasing exceptional capability in navigating
the complexities of the physical world. 3UR-LLM directly receives 3D point
cloud as input and project 3D features fused with text instructions into a
manageable set of tokens. Considering the computation burden derived from these
hybrid tokens, we design a 3D compressor module to cohesively compress the 3D
spatial cues and textual narrative. 3UR-LLM achieves promising performance with
respect to the previous SOTAs, for instance, 3UR-LLM exceeds its counterparts
by 7.1% CIDEr on ScanQA, while utilizing fewer training resources. The code
and model weights for 3UR-LLM and the 3DS-160K benchmark are available at
3UR-LLM.
