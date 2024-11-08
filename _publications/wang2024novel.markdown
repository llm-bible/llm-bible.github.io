---
layout: publication
title: 'SUBLLM: A Novel Efficient Architecture With Token Sequence Subsampling For LLM'
authors: Wang Quandong, Yuan Yuxuan, Yang Xiaoyu, Zhang Ruike, Zhao Kang, Liu Wei, Luan Jian, Povey Daniel, Wang Bin
conference: "Arxiv"
year: 2024
bibkey: wang2024novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06571"}
  - {name: "Code", url: "https://github.com/XiaoMi/subllm"}
tags: ['Efficiency And Optimization', 'Few Shot', 'Has Code', 'Model Architecture', 'Tools', 'Training Techniques']
---
While Large Language Models (LLMs) have achieved remarkable success in
various fields, the efficiency of training and inference remains a major
challenge. To address this issue, we propose SUBLLM, short for
Subsampling-Upsampling-Bypass Large Language Model, an innovative architecture
that extends the core decoder-only framework by incorporating subsampling,
upsampling, and bypass modules. The subsampling modules are responsible for
shortening the sequence, while the upsampling modules restore the sequence
length, and the bypass modules enhance convergence. In comparison to LLaMA, the
proposed SUBLLM exhibits significant enhancements in both training and
inference speeds as well as memory usage, while maintaining competitive
few-shot performance. During training, SUBLLM increases speeds by 26% and cuts
memory by 10GB per GPU. In inference, it boosts speeds by up to 37% and reduces
memory by 1GB per GPU. The training and inference speeds can be enhanced by 34%
and 52% respectively when the context window is expanded to 8192. Our code is
available at https://github.com/XiaoMi/subllm.
