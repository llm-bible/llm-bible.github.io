---
layout: publication
title: 'Ppllava: Varied Video Sequence Understanding With Prompt Guidance'
authors: Ruyang Liu, Haoran Tang, Haibo Liu, Yixiao Ge, Ying Shan, Chen Li, Jiankun Yang
conference: "Arxiv"
year: 2024
bibkey: liu2024varied
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02327'}
  - {name: "Code", url: 'https://github.com/farewellthree/PPLLaVA'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
The past year has witnessed the significant advancement of video-based large
language models. However, the challenge of developing a unified model for both
short and long video understanding remains unresolved. Most existing video LLMs
cannot handle hour-long videos, while methods custom for long videos tend to be
ineffective for shorter videos and images. In this paper, we identify the key
issue as the redundant content in videos. To address this, we propose a novel
pooling strategy that simultaneously achieves token compression and
instruction-aware visual feature aggregation. Our model is termed Prompt-guided
Pooling LLaVA, or PPLLaVA for short. Specifically, PPLLaVA consists of three
core components: the CLIP-based visual-prompt alignment that extracts visual
information relevant to the user's instructions, the prompt-guided pooling that
compresses the visual sequence to arbitrary scales using convolution-style
pooling, and the clip context extension designed for lengthy prompt common in
visual dialogue. Moreover, our codebase also integrates the most advanced video
Direct Preference Optimization (DPO) and visual interleave training. Extensive
experiments have validated the performance of our model. With superior
throughput and only 1024 visual context, PPLLaVA achieves better results on
image benchmarks as a video LLM, while achieving state-of-the-art performance
across various video benchmarks, excelling in tasks ranging from caption
generation to multiple-choice questions, and handling video lengths from
seconds to hours. Codes have been available at
https://github.com/farewellthree/PPLLaVA.
