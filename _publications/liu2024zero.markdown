---
layout: publication
title: 'Zero-to-strong Generalization: Eliciting Strong Capabilities Of Large Language Models Iteratively Without Gold Labels'
authors: Chaoqun Liu, Qin Chao, Wenxuan Zhang, Xiaobao Wu, Boyang Li, Anh Tuan Luu, Lidong Bing
conference: "Arxiv"
year: 2024
bibkey: liu2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12425"}
tags: ['Fine-Tuning', 'Tools', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated remarkable performance through
supervised fine-tuning or in-context learning using gold labels. However, this
paradigm is limited by the availability of gold labels, while in certain
scenarios, LLMs may need to perform tasks that are too complex for humans to
provide such labels. To tackle this challenge, this study explores whether
solely utilizing unlabeled data can elicit strong model capabilities. We
propose a new paradigm termed zero-to-strong generalization. We iteratively
prompt LLMs to annotate unlabeled data and retain high-quality labels by
filtering. Surprisingly, we obverse that this iterative process gradually
unlocks LLMs' potential on downstream tasks. Our experiments on extensive
classification and reasoning tasks confirm the effectiveness of our proposed
framework. Our analysis indicates that this paradigm is effective for both
in-context learning and fine-tuning, and for various model sizes.
