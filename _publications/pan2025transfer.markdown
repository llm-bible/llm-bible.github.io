---
layout: publication
title: 'Transfer Between Modalities With Metaqueries'
authors: Xichen Pan, Satya Narayan Shukla, Aashu Singh, Zhuokai Zhao, Shlok Kumar Mishra, Jialiang Wang, Zhiyang Xu, Jiuhai Chen, Kunpeng Li, Felix Juefei-xu, Ji Hou, Saining Xie
conference: "Arxiv"
year: 2025
bibkey: pan2025transfer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06256"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'RAG', 'Merging', 'GPT', 'Pretraining Methods', 'Applications']
---
Unified multimodal models aim to integrate understanding (text output) and
generation (pixel output), but aligning these different modalities within a
single architecture often demands complex training recipes and careful data
balancing. We introduce MetaQueries, a set of learnable queries that act as an
efficient interface between autoregressive multimodal LLMs (MLLMs) and
diffusion models. MetaQueries connects the MLLM's latents to the diffusion
decoder, enabling knowledge-augmented image generation by leveraging the MLLM's
deep understanding and reasoning capabilities. Our method simplifies training,
requiring only paired image-caption data and standard diffusion objectives.
Notably, this transfer is effective even when the MLLM backbone remains frozen,
thereby preserving its state-of-the-art multimodal understanding capabilities
while achieving strong generative performance. Additionally, our method is
flexible and can be easily instruction-tuned for advanced applications such as
image editing and subject-driven generation.
