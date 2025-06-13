---
layout: publication
title: 'Cascade Reward Sampling For Efficient Decoding-time Alignment'
authors: Bolian Li, Yifan Wang, Anamika Lochab, Ananth Grama, Ruqi Zhang
conference: "Arxiv"
year: 2024
bibkey: li2024cascade
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.16306'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Aligning large language models (LLMs) with human preferences is essential for
their applications. Recently, decoding-time alignment has emerged as an
effective plug-and-play technique that avoids fine-tuning model parameters.
This approach retains the general utility of pretrained LLMs but often suffers
from significant inefficiencies during decoding, primarily due to wasted token
generation and excessive reward evaluations. To address these challenges, we
introduce Cascade Reward Sampling (CARDS) to resolve both efficiency
bottlenecks in decoding-time alignment. Specifically, we develop a
segment-level rejection sampling algorithm that minimizes redundant
computations of both LLMs and reward models (RMs). Central to CARDS is an
uncertainty-based segmentation mechanism, which ensures the accuracy of RMs
evaluations on incomplete segments. Furthermore, we provide a detailed analysis
of reward scores on segments to elucidate the improved alignment performance.
Experimental results demonstrate that CARDS significantly improves decoding
efficiency, alignment quality, and general utility compared to existing
decoding-time alignment methods, achieving approximately a 70% reduction in
decoding time and over 90% win-ties in utility and safety benchmarks.
