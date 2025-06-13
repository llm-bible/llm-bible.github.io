---
layout: publication
title: 'Ranking-aware Adapter For Text-driven Image Ordering With CLIP'
authors: Wei-hsiang Yu, Yen-yu Lin, Ming-hsuan Yang, Yi-hsuan Tsai
conference: "Arxiv"
year: 2024
bibkey: yu2024ranking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06760"}
tags: ['Applications', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Multimodal Models', 'Prompting']
---
Recent advances in vision-language models (VLMs) have made significant
progress in downstream tasks that require quantitative concepts such as facial
age estimation and image quality assessment, enabling VLMs to explore
applications like image ranking and retrieval. However, existing studies
typically focus on the reasoning based on a single image and heavily depend on
text prompting, limiting their ability to learn comprehensive understanding
from multiple images. To address this, we propose an effective yet efficient
approach that reframes the CLIP model into a learning-to-rank task and
introduces a lightweight adapter to augment CLIP for text-guided image ranking.
Specifically, our approach incorporates learnable prompts to adapt to new
instructions for ranking purposes and an auxiliary branch with ranking-aware
attention, leveraging text-conditioned visual differences for additional
supervision in image ranking. Our ranking-aware adapter consistently
outperforms fine-tuned CLIPs on various tasks and achieves competitive results
compared to state-of-the-art models designed for specific tasks like facial age
estimation and image quality assessment. Overall, our approach primarily
focuses on ranking images with a single instruction, which provides a natural
and generalized way of learning from visual differences across images,
bypassing the need for extensive text prompts tailored to individual tasks.
Code is available: github.com/uynaes/RankingAwareCLIP.
