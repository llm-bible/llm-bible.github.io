---
layout: publication
title: 'AIM: Adaptive Inference Of Multi-modal Llms Via Token Merging And Pruning'
authors: Yiwu Zhong, Zhuoming Liu, Yin Li, Liwei Wang
conference: "Arxiv"
year: 2024
bibkey: zhong2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03248"}
  - {name: "Code", url: "https://github.com/LaVi-Lab/AIM"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Merging', 'Pruning', 'Has Code']
---
Large language models (LLMs) have enabled the creation of multi-modal LLMs
that exhibit strong comprehension of visual data such as images and videos.
However, these models usually rely on extensive visual tokens from visual
encoders, leading to high computational demands, which limits their
applicability in resource-constrained environments and for long-context tasks.
In this work, we propose a training-free adaptive inference method for
multi-modal LLMs that can accommodate a broad range of efficiency requirements
with a minimum performance drop. Our method consists of a) iterative token
merging based on embedding similarity before LLMs, and b) progressive token
pruning within LLM layers based on multi-modal importance. With a minimalist
design, our method can be applied to both video and image LLMs. Extensive
experiments on diverse video and image benchmarks demonstrate that, our method
substantially reduces computation load (e.g., a \\(\textbf\{7-fold\}\\) reduction in
FLOPs) while preserving the performance of video and image LLMs. Further, under
a similar computational cost, our method outperforms the state-of-the-art
methods in long video understanding (e.g., \\(\textbf\{+4.6\}\\) on MLVU).
Additionally, our in-depth analysis provides insights into token redundancy and
LLM layer behaviors, offering guidance for future research in designing
efficient multi-modal LLMs. Our code will be available at
https://github.com/LaVi-Lab/AIM.
