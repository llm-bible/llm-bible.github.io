---
layout: publication
title: 'Chatrex: Taming Multimodal LLM For Joint Perception And Understanding'
authors: Qing Jiang, Gen Luo, Yuqin Yang, Yuda Xiong, Yihao Chen, Zhaoyang Zeng, Tianhe Ren, Lei Zhang
conference: "Arxiv"
year: 2024
bibkey: jiang2024taming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18363"}
  - {name: "Code", url: "https://github.com/IDEA-Research/ChatRex"}
tags: ['Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'Has Code', 'Applications']
---
Perception and understanding are two pillars of computer vision. While
multimodal large language models (MLLM) have demonstrated remarkable visual
understanding capabilities, they arguably lack accurate perception abilities,
e.g. the stage-of-the-art model Qwen2-VL only achieves a 43.9 recall rate on
the COCO dataset, limiting many tasks requiring the combination of perception
and understanding. In this work, we aim to bridge this perception gap from both
model designing and data development perspectives. We first introduce ChatRex,
an MLLM with a decoupled perception design. Instead of having the LLM directly
predict box coordinates, we feed the output boxes from a universal proposal
network into the LLM, allowing it to output the corresponding box indices to
represent its detection results, turning the regression task into a
retrieval-based task that LLM handles more proficiently. From the data
perspective, we build a fully automated data engine and construct the
Rexverse-2M dataset which possesses multiple granularities to support the joint
training of perception and understanding. After a three-stage training
approach, ChatRex demonstrates strong perception and understanding performance,
and the combination of these two capabilities also unlocks many attractive
applications, demonstrating their complementary roles in MLLM. Code is
available at https://github.com/IDEA-Research/ChatRex.
