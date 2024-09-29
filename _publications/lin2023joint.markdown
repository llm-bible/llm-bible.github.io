---
layout: publication
title: SPHINX The Joint Mixing Of Weights Tasks And Visual Embeddings For Multi45;modal Large Language Models
authors: Lin Ziyi, Liu Chris, Zhang Renrui, Gao Peng, Qiu Longtian, Xiao Han, Qiu Han, Lin Chen, Shao Wenqi, Chen Keqin, Han Jiaming, Huang Siyuan, Zhang Yichi, He Xuming, Li Hongsheng, Qiao Yu
conference: "Arxiv"
year: 2023
bibkey: lin2023joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07575"}
  - {name: "Code", url: "https://github.com/Alpha&#45;VLLM/LLaMA2&#45;Accessory"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
We present SPHINX a versatile multi45;modal large language model (MLLM) with a joint mixing of model weights tuning tasks and visual embeddings. First for stronger vision45;language alignment we unfreeze the large language model (LLM) during pre45;training and introduce a weight mix strategy between LLMs trained by real45;world and synthetic data. By directly integrating the weights from two domains the mixed LLM can efficiently incorporate diverse semantics with favorable robustness. Then to enable multi45;purpose capabilities we mix a variety of tasks for joint visual instruction tuning and design task45;specific instructions to avoid inter45;task conflict. In addition to the basic visual question answering we include more challenging tasks such as region45;level understanding caption grounding document layout detection and human pose estimation contributing to mutual enhancement over different scenarios. Additionally we propose to extract comprehensive visual embeddings from various network architectures pre45;training paradigms and information granularity providing language models with more robust image representations. Based on our proposed joint mixing SPHINX exhibits superior multi45;modal understanding capabilities on a wide range of applications. On top of this we further propose an efficient strategy aiming to better capture fine45;grained appearances of high45;resolution images. With a mixing of different scales and high45;resolution sub45;images SPHINX attains exceptional visual parsing and reasoning performance on existing evaluation benchmarks. We hope our work may cast a light on the exploration of joint mixing in future MLLM research. Code is released at https://github.com/Alpha&#45;VLLM/LLaMA2&#45;Accessory.
