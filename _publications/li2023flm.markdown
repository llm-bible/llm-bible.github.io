---
layout: publication
title: 'FLM-101B: An Open LLM And How To Train It With $100K Budget'
authors: Xiang Li, Yiqun Yao, Xin Jiang, Xuezhi Fang, Xuying Meng, Siqi Fan, Peng Han, Jing Li, Li Du, Bowen Qin, Zheng Zhang, Aixin Sun, Yequan Wang
conference: "Arxiv"
year: 2023
bibkey: li2023flm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03852"}
tags: ['Training Techniques', 'Pre-Training', 'Multimodal Models']
---
Large language models (LLMs) are considered important approaches towards
foundational machine intelligence, achieving remarkable success in Natural
Language Processing and multimodal tasks, among others. However, the carbon
footprints and financial costs originating from heavy pre-training computation
is a non-negligible issue. Progressive training methods, inspired by the
neurogenesis process that grows neural structures, have shown potential to
accelerate LLM pre-training. However, the algorithms, implementation, and
practices for progressively training LLMs beyond 100B parameters remain
underexplored. In this paper, we show that our model, namely FLM-101B, trained
with our growth strategy under a budget of \$100K, reaches 80% of the
baselines' performances with only 10% of their floating-point operations. We
believe that further studies on progressive training will benefit the community
by cutting down the costs and promoting green AI. The checkpoint of FLM-101B is
released at https://huggingface.co/CofeAI/FLM-101B.
