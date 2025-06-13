---
layout: publication
title: 'Timesearch: Hierarchical Video Search With Spotlight And Reflection For Human-like Long Video Understanding'
authors: Junwen Pan, Rui Zhang, Xin Wan, Yuan Zhang, Ming Lu, Qi She
conference: "Arxiv"
year: 2025
bibkey: pan2025hierarchical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01407'}
tags: ['RAG', 'GPT', 'Tools', 'Pretraining Methods']
---
Large video-language models (LVLMs) have shown remarkable performance across
various video-language tasks. However, they encounter significant challenges
when processing long videos because of the large number of video frames
involved. Downsampling long videos in either space or time can lead to visual
hallucinations, making it difficult to accurately interpret long videos.
Motivated by human hierarchical temporal search strategies, we propose
\textbf\{TimeSearch\}, a novel framework enabling LVLMs to understand long videos
in a human-like manner. TimeSearch integrates two human-like primitives into a
unified autoregressive LVLM: 1) \textbf\{Spotlight\} efficiently identifies
relevant temporal events through a Temporal-Augmented Frame Representation
(TAFR), explicitly binding visual features with timestamps; 2)
\textbf\{Reflection\} evaluates the correctness of the identified events,
leveraging the inherent temporal self-reflection capabilities of LVLMs.
TimeSearch progressively explores key events and prioritizes temporal search
based on reflection confidence. Extensive experiments on challenging long-video
benchmarks confirm that TimeSearch substantially surpasses previous
state-of-the-art, improving the accuracy from 41.8% to 51.5% on the LVBench.
Additionally, experiments on temporal grounding demonstrate that appropriate
TAFR is adequate to effectively stimulate the surprising temporal grounding
ability of LVLMs in a simpler yet versatile manner, which improves mIoU on
Charades-STA by 11.8%. The code will be released.
