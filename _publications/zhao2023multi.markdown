---
layout: publication
title: Multi-modal In-context Learning Makes An Ego-evolving Scene Text Recognizer
authors: Zhao Zhen, Tang Jingqun, Lin Chunhui, Wu Binghong, Huang Can, Liu Hao, Tan Xin, Zhang Zhizhong, Xie Yuan
conference: "Arxiv"
year: 2023
bibkey: zhao2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13120"}
  - {name: "Code", url: "https://github.com/bytedance/E2STR"}
tags: ['Fine Tuning', 'Has Code', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Scene text recognition (STR) in the wild frequently encounters challenges when coping with domain variations font diversity shape deformations etc. A straightforward solution is performing model fine-tuning tailored to a specific scenario but it is computationally intensive and requires multiple model copies for various scenarios. Recent studies indicate that large language models (LLMs) can learn from a few demonstration examples in a training-free manner termed In-Context Learning (ICL). Nevertheless applying LLMs as a text recognizer is unacceptably resource-consuming. Moreover our pilot experiments on LLMs show that ICL fails in STR mainly attributed to the insufficient incorporation of contextual information from diverse samples in the training stage. To this end we introduce E^2STR a STR model trained with context-rich scene text sequences where the sequences are generated via our proposed in-context training strategy. E^2STR demonstrates that a regular-sized model is sufficient to achieve effective ICL capabilities in STR. Extensive experiments show that E^2STR exhibits remarkable training-free adaptation in various scenarios and outperforms even the fine-tuned state-of-the-art approaches on public benchmarks. The code is released at https://github.com/bytedance/E2STR .
