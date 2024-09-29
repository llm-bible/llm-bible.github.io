---
layout: publication
title: 'Elitr-bench: A Meeting Assistant Benchmark For Long-context Language Models'
authors: Thonet Thibaut, Rozen Jos, Besacier Laurent
conference: "Arxiv"
year: 2024
bibkey: thonet2024elitr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.20262"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Research on Large Language Models (LLMs) has recently witnessed an increasing interest in extending models context size to better capture dependencies within long documents. While benchmarks have been proposed to assess long-range abilities existing efforts primarily considered generic tasks that are not necessarily aligned with real-world applications. In contrast our work proposes a new benchmark for long-context LLMs focused on a practical meeting assistant scenario. In this scenario the long contexts consist of transcripts obtained by automatic speech recognition presenting unique challenges for LLMs due to the inherent noisiness and oral nature of such data. Our benchmark named ELITR-Bench augments the existing ELITR corpus transcripts with 271 manually crafted questions and their ground-truth answers. Our experiments with recent long-context LLMs on ELITR-Bench highlight a gap between open-source and proprietary models especially when questions are asked sequentially within a conversation. We also provide a thorough analysis of our GPT-4-based evaluation method encompassing insights from a crowdsourcing study. Our findings suggest that while GPT-4s evaluation scores are correlated with human judges its ability to differentiate among more than three score levels may be limited.
