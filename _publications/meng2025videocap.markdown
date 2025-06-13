---
layout: publication
title: 'Videocap-r1: Enhancing Mllms For Video Captioning Via Structured Thinking'
authors: Desen Meng, Rui Huang, Zhilin Dai, Xinhao Li, Yifan Xu, Jun Zhang, Zhenpeng Huang, Meng Zhang, Lingshu Zhang, Yi Liu, Limin Wang
conference: "Arxiv"
year: 2025
bibkey: meng2025videocap
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01725"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Prompting']
---
While recent advances in reinforcement learning have significantly enhanced reasoning capabilities in large language models (LLMs), these techniques remain underexplored in multi-modal LLMs for video captioning. This paper presents the first systematic investigation of GRPO-based RL post-training for video MLLMs, with the goal of enhancing video MLLMs' capability of describing actions in videos. Specifically, we develop the VideoCap-R1, which is prompted to first perform structured thinking that analyzes video subjects with their attributes and actions before generating complete captions, supported by two specialized reward mechanisms: a LLM-free think scorer evaluating the structured thinking quality and a LLM-assisted caption scorer assessing the output quality. The RL training framework effectively establishes the connection between structured reasoning and comprehensive description generation, enabling the model to produce captions with more accurate actions. Our experiments demonstrate that VideoCap-R1 achieves substantial improvements over the Qwen2VL-7B baseline using limited samples (1.5k) across multiple video caption benchmarks (DREAM1K: +4.4 event F1, VDC: +4.2 Acc, CAREBENCH: +3.1 action F1, +6.9 object F1) while consistently outperforming the SFT-trained counterparts, confirming GRPO's superiority in enhancing MLLMs' captioning capabilities.
