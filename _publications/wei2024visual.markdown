---
layout: publication
title: 'Visual Context Window Extension: A New Perspective For Long Video Understanding'
authors: Hongchen Wei, Zhenzhong Chen
conference: "Arxiv"
year: 2024
bibkey: wei2024visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.20018'}
tags: ['Training Techniques', 'Model Architecture', 'Multimodal Models', 'GPT']
---
Large Multimodal Models (LMMs) have demonstrated impressive performance in
short video understanding tasks but face great challenges when applied to long
video understanding. In contrast, Large Language Models (LLMs) exhibit
outstanding capabilities in modeling long texts. Existing work attempts to
address this issue by introducing long video-text pairs during training.
However, these approaches require substantial computational and data resources.
In this paper, we tackle the challenge of long video understanding from the
perspective of context windows, aiming to apply LMMs to long video tasks
without retraining on long video datasets. We first conduct an in-depth
analysis of why pretrained LMMs struggle to understand lengthy video content,
identifying that discrepancies between visual and language modalities lead to
different context windows for visual and language tokens, making it difficult
to directly extend the visual tokens to match the language context window.
Based on this, we propose to adapt LMMs for long video understanding tasks by
extending the visual context window, eliminating the need for retraining on
large scalelong video datasets. To further mitigate the significant memory
consumption caused by long sequences, we introduce a progressive pooling
inference strategy that selectively adjusts the spatial resolution of frame
embeddings, reducing the number of visual tokens while retaining important
spatial information. Across multiple long video understanding benchmarks, our
method consistently improves the performance as the number of video frames
increases. On the MLVU benchmark, our method outperforms GPT-4o, even though
our model size is only 7B. Additionally, in the 256-frame setting, our method
reduces memory usage by approximately 45% compared to the baseline, without
introducing any performance loss.
