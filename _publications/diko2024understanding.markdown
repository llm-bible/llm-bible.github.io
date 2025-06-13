---
layout: publication
title: 'Rewind: Understanding Long Videos With Instructed Learnable Memory'
authors: Anxhelo Diko, Tinghuai Wang, Wassim Swaileh, Shiyan Sun, Ioannis Patras
conference: "Arxiv"
year: 2024
bibkey: diko2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15556"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Multimodal Models']
---
Vision-Language Models (VLMs) are crucial for applications requiring
integrated understanding textual and visual information. However, existing VLMs
struggle with long videos due to computational inefficiency, memory
limitations, and difficulties in maintaining coherent understanding across
extended sequences. To address these challenges, we introduce ReWind, a novel
memory-based VLM designed for efficient long video understanding while
preserving temporal fidelity. ReWind operates in a two-stage framework. In the
first stage, ReWind maintains a dynamic learnable memory module with a novel
\textbf\{read-perceive-write\} cycle that stores and updates instruction-relevant
visual information as the video unfolds. This module utilizes learnable queries
and cross-attentions between memory contents and the input stream, ensuring low
memory requirements by scaling linearly with the number of tokens. In the
second stage, we propose an adaptive frame selection mechanism guided by the
memory content to identify instruction-relevant key moments. It enriches the
memory representations with detailed spatial information by selecting a few
high-resolution frames, which are then combined with the memory contents and
fed into a Large Language Model (LLM) to generate the final answer. We
empirically demonstrate ReWind's superior performance in visual question
answering (VQA) and temporal grounding tasks, surpassing previous methods on
long video benchmarks. Notably, ReWind achieves a +13% score gain and a +12%
accuracy improvement on the MovieChat-1K VQA dataset and an +8% mIoU increase
on Charades-STA for temporal grounding.
