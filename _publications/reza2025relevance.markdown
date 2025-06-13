---
layout: publication
title: 'REEF: Relevance-aware And Efficient LLM Adapter For Video Understanding'
authors: Sakib Reza, Xiyun Song, Heather Yu, Zongfang Lin, Mohsen Moghaddam, Octavia Camps
conference: "Arxiv"
year: 2025
bibkey: reza2025relevance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05491"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications']
---
Integrating vision models into large language models (LLMs) has sparked
significant interest in creating vision-language foundation models, especially
for video understanding. Recent methods often utilize memory banks to handle
untrimmed videos for video-level understanding. However, they typically
compress visual memory using similarity-based greedy approaches, which can
overlook the contextual importance of individual tokens. To address this, we
introduce an efficient LLM adapter designed for video-level understanding of
untrimmed videos that prioritizes the contextual relevance of spatio-temporal
tokens. Our framework leverages scorer networks to selectively compress the
visual memory bank and filter spatial tokens based on relevance, using a
differentiable Top-K operator for end-to-end training. Across three key
video-level understanding tasks\\(\unicode\{x2013\}\\) untrimmed video
classification, video question answering, and video
captioning\\(\unicode\{x2013\}\\)our method achieves competitive or superior results
on four large-scale datasets while reducing computational overhead by up to
34%. The code will be available soon on GitHub.
