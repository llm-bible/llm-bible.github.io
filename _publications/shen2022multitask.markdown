---
layout: publication
title: Multitask Vision-language Prompt Tuning
authors: Sheng Shen et al.
conference: Arxiv
year: 2022
citations: 15
bibkey: shen2022multitask
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.11720'}, {name: Code,
    url: 'https://github.com/sIncerass/MVLPT'}]
tags: [Multimodal Models, Prompting, Few-Shot]
---
Prompt Tuning, conditioning on task-specific learned prompt vectors, has
emerged as a data-efficient and parameter-efficient method for adapting large
pretrained vision-language models to multiple downstream tasks. However,
existing approaches usually consider learning prompt vectors for each task
independently from scratch, thereby failing to exploit the rich shareable
knowledge across different vision-language tasks. In this paper, we propose
multitask vision-language prompt tuning (MVLPT), which incorporates cross-task
knowledge into prompt tuning for vision-language models. Specifically, (i) we
demonstrate the effectiveness of learning a single transferable prompt from
multiple source tasks to initialize the prompt for each target task; (ii) we
show many target tasks can benefit each other from sharing prompt vectors and
thus can be jointly learned via multitask prompt tuning. We benchmark the
proposed MVLPT using three representative prompt tuning methods, namely text
prompt tuning, visual prompt tuning, and the unified vision-language prompt
tuning. Results in 20 vision tasks demonstrate that the proposed approach
outperforms all single-task baseline prompt tuning methods, setting the new
state-of-the-art on the few-shot ELEVATER benchmarks and cross-task
generalization benchmarks. To understand where the cross-task knowledge is most
effective, we also conduct a large-scale study on task transferability with 20
vision tasks in 400 combinations for each prompt tuning method. It shows that
the most performant MVLPT for each prompt tuning method prefers different task
combinations and many tasks can benefit each other, depending on their visual
similarity and label similarity. Code is available at
https://github.com/sIncerass/MVLPT.