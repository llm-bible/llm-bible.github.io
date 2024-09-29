---
layout: publication
title: 'Diffusion Language Models Can Perform Many Tasks With Scaling And Instruction-finetuning'
authors: Ye Jiasheng, Zheng Zaixiang, Bao Yu, Qian Lihua, Gu Quanquan
conference: "Arxiv"
year: 2023
bibkey: ye2023diffusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12219"}
tags: ['BERT', 'Few Shot', 'GPT', 'In Context Learning', 'Language Modeling', 'Masked Language Model', 'Merging', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
The recent surge of generative AI has been fueled by the generative power of diffusion probabilistic models and the scalable capabilities of large language models. Despite their potential it remains elusive whether diffusion language models can solve general language tasks comparable to their autoregressive counterparts. This paper demonstrates that scaling diffusion models w.r.t. data sizes and tasks can effectively make them strong language learners. We build competent diffusion language models at scale by first acquiring knowledge from massive data via masked language modeling pretraining thanks to their intrinsic connections. We then reprogram pretrained masked language models into diffusion language models via diffusive adaptation wherein task-specific finetuning and instruction finetuning are explored to unlock their versatility in solving general language tasks. Experiments show that scaling diffusion language models consistently improves performance across downstream language tasks. We further discover that instruction finetuning can elicit zero-shot and few-shot in-context learning abilities that help tackle many unseen tasks by following natural language instructions and show promise in advanced and challenging abilities such as reasoning.
