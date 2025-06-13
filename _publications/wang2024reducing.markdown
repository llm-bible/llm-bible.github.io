---
layout: publication
title: 'Retake: Reducing Temporal And Knowledge Redundancy For Long Video Understanding'
authors: Xiao Wang, Qingyi Si, Jianlong Wu, Shiyu Zhu, Li Cao, Liqiang Nie
conference: "Arxiv"
year: 2024
bibkey: wang2024reducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.20504'}
  - {name: "Code", url: 'https://github.com/SCZwangxiao/video-ReTaKe'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Reinforcement Learning']
---
Video Large Language Models (VideoLLMs) have made significant strides in
video understanding but struggle with long videos due to the limitations of
their backbone LLMs. Existing solutions rely on length extrapolation, which is
memory-constrained, or visual token compression, which primarily leverages
low-level temporal redundancy while overlooking the more effective high-level
knowledge redundancy. To address this, we propose \\(\textbf\{ReTaKe\}\\), a
training-free method with two novel modules DPSelect and PivotKV, to jointly
reduce both temporal visual redundancy and knowledge redundancy for video
compression. To align with the way of human temporal perception, DPSelect
identifies keyframes based on inter-frame distance peaks. To leverage LLMs'
learned prior knowledge, PivotKV marks the keyframes as pivots and compress
non-pivot frames by pruning low-attention tokens in their KV cache. ReTaKe
enables VideoLLMs to process 8 times longer frames (up to 2048), outperforming
similar-sized models by 3-5% and even rivaling much larger ones on VideoMME,
MLVU, LongVideoBench, and LVBench. Moreover, by overlapping compression
operations with prefilling, ReTaKe introduces only ~10% prefilling latency
overhead while reducing decoding latency by ~20%. Our code is available at
https://github.com/SCZwangxiao/video-ReTaKe.
