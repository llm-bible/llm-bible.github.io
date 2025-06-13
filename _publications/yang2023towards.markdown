---
layout: publication
title: 'Towards Difficulty-agnostic Efficient Transfer Learning For Vision-language Models'
authors: Yongjin Yang, Jongwoo Ko, Se-young Yun
conference: "Arxiv"
year: 2023
bibkey: yang2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.15569"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Vision-language models (VLMs) like CLIP have demonstrated remarkable
applicability across a variety of downstream tasks, including zero-shot image
classification. Recently, the use of prompts or adapters for efficient transfer
learning (ETL) has gained significant attention for effectively adapting to
downstream tasks. However, previous studies have overlooked the challenge of
varying transfer difficulty of downstream tasks. In this paper, we empirically
analyze how each ETL method behaves with respect to transfer difficulty. Our
observations indicate that utilizing vision prompts and text adapters is
crucial for adaptability and generalizability in domains with high difficulty.
Also, by applying an adaptive ensemble approach that integrates task-adapted
VLMs with pre-trained VLMs and strategically leverages more general knowledge
in low-difficulty and less in high-difficulty domains, we consistently enhance
performance across both types of domains. Based on these observations, we
propose an adaptive ensemble method that combines visual prompts and text
adapters with pre-trained VLMs, tailored by transfer difficulty, to achieve
optimal performance for any target domain. Upon experimenting with extensive
benchmarks, our method consistently outperforms all baselines, particularly on
unseen tasks, demonstrating its effectiveness.
