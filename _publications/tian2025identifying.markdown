---
layout: publication
title: 'Identifying And Mitigating Position Bias Of Multi-image Vision-language Models'
authors: Xinyu Tian, Shu Zou, Zhaoyuan Yang, Jing Zhang
conference: "Arxiv"
year: 2025
bibkey: tian2025identifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13792"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Ethics and Bias', 'Attention Mechanism']
---
The evolution of Large Vision-Language Models (LVLMs) has progressed from
single to multi-image reasoning. Despite this advancement, our findings
indicate that LVLMs struggle to robustly utilize information across multiple
images, with predictions significantly affected by the alteration of image
positions. To further explore this issue, we introduce Position-wise Question
Answering (PQA), a meticulously designed task to quantify reasoning
capabilities at each position. Our analysis reveals a pronounced position bias
in LVLMs: open-source models excel in reasoning with images positioned later
but underperform with those in the middle or at the beginning, while
proprietary models show improved comprehension for images at the beginning and
end but struggle with those in the middle. Motivated by this, we propose SoFt
Attention (SoFA), a simple, training-free approach that mitigates this bias by
employing linear interpolation between inter-image causal attention and
bidirectional counterparts. Experimental results demonstrate that SoFA reduces
position bias and enhances the reasoning performance of existing LVLMs.
