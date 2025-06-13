---
layout: publication
title: 'Linvt: Empower Your Image-level Large Language Model To Understand Videos'
authors: Lishuai Gao, Yujie Zhong, Yingsen Zeng, Haoxian Tan, Dengjie Li, Zheng Zhao
conference: "Arxiv"
year: 2024
bibkey: gao2024empower
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05185"}
tags: ['Training Techniques']
---
Large Language Models (LLMs) have been widely used in various tasks,
motivating us to develop an LLM-based assistant for videos. Instead of training
from scratch, we propose a module to transform arbitrary well-trained
image-based LLMs into video-LLMs (after being trained on video data). To better
adapt image-LLMs for processing videos, we introduce two design principles:
linear transformation to preserve the original visual-language alignment and
representative information condensation from redundant video content. Guided by
these principles, we propose a plug-and-play Linear Video Tokenizer(LinVT),
which enables existing image-LLMs to understand videos. We benchmark LinVT with
six recent visual LLMs: Aquila, Blip-3, InternVL2, Mipha, Molmo and Qwen2-VL,
showcasing the high compatibility of LinVT. LinVT-based LLMs achieve
state-of-the-art performance across various video benchmarks, illustrating the
effectiveness of LinVT in multi-modal video understanding.
