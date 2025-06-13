---
layout: publication
title: 'Think Before You Diffuse: Llms-guided Physics-aware Video Generation'
authors: Ke Zhang, Cihan Xiao, Yiqun Mei, Jiacong Xu, Vishal M. Patel
conference: "Arxiv"
year: 2025
bibkey: zhang2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21653"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Recent video diffusion models have demonstrated their great capability in generating visually-pleasing results, while synthesizing the correct physical effects in generated videos remains challenging. The complexity of real-world motions, interactions, and dynamics introduce great difficulties when learning physics from data. In this work, we propose DiffPhy, a generic framework that enables physically-correct and photo-realistic video generation by fine-tuning a pre-trained video diffusion model. Our method leverages large language models (LLMs) to explicitly reason a comprehensive physical context from the text prompt and use it to guide the generation. To incorporate physical context into the diffusion model, we leverage a Multimodal large language model (MLLM) as a supervisory signal and introduce a set of novel training objectives that jointly enforce physical correctness and semantic consistency with the input text. We also establish a high-quality physical video dataset containing diverse phyiscal actions and events to facilitate effective finetuning. Extensive experiments on public benchmarks demonstrate that DiffPhy is able to produce state-of-the-art results across diverse physics-related scenarios. Our project page is available at https://bwgzk-keke.github.io/DiffPhy/
