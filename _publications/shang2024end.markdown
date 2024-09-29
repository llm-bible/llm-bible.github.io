---
layout: publication
title: "An End-to-end Speech Summarization Using Large Language Model"
authors: Shang Hengchao, Li Zongyao, Guo Jiaxin, Li Shaojun, Rao Zhiqiang, Luo Yuanchang, Wei Daimeng, Yang Hao
conference: "Arxiv"
year: 2024
bibkey: shang2024end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02005"}
tags: ['Applications', 'Merging', 'Multimodal Models', 'Training Techniques']
---
Abstractive Speech Summarization (SSum) aims to generate human-like text summaries from spoken content. It encounters difficulties in handling long speech input and capturing the intricate cross-modal mapping between long speech inputs and short text summaries. Research on large language models (LLMs) and multimodal information fusion has provided new insights for addressing these challenges. In this paper we propose an end-to-end SSum model that utilizes Q-Former as a connector for the audio-text modality and employs LLMs to generate text summaries directly from speech features. We adopt a multi-stage training approach that includes LLM based ASR and Text Summarization (TSum) tasks as auxiliary tasks. ASR tasks are used to align feature spaces and enhance the LLMs ability to handle longer speech. Then we utilize a curriculum learning strategy to facilitate the models transition from TSum to SSum. Finally our model achieves competitive performance on the How-2 dataset.
