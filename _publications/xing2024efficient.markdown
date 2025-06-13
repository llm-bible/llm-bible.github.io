---
layout: publication
title: 'EFUF: Efficient Fine-grained Unlearning Framework For Mitigating Hallucinations In Multimodal Large Language Models'
authors: Shangyu Xing, Fei Zhao, Zhen Wu, Tuo An, Weihao Chen, Chunhui Li, Jianbing Zhang, Xinyu Dai
conference: "Arxiv"
year: 2024
bibkey: xing2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09801"}
tags: ['Multimodal Models', 'Model Architecture', 'Attention Mechanism', 'Tools']
---
Multimodal large language models (MLLMs) have attracted increasing attention
in the past few years, but they may still generate descriptions that include
objects not present in the corresponding images, a phenomenon known as object
hallucination. To eliminate hallucinations, existing methods manually annotate
paired responses with and without hallucinations, and then employ various
alignment algorithms to improve the alignment capability between images and
text. However, they not only demand considerable computation resources during
the finetuning stage but also require expensive human annotation to construct
paired data needed by the alignment algorithms. To address these issues, we
borrow the idea of unlearning and propose an efficient fine-grained unlearning
framework (EFUF), which can eliminate hallucinations without the need for
paired data. Extensive experiments show that our method consistently reduces
hallucinations while preserving the generation quality with modest
computational overhead. Our code and datasets will be publicly available.
