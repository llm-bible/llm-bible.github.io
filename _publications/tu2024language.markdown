---
layout: publication
title: 'MLAN: Language-based Instruction Tuning Improves Zero-shot Generalization Of Multimodal Large Language Models'
authors: Jianhong Tu, Zhuohao Ni, Nicholas Crispino, Zihao Yu, Michael Bendersky, Beliz Gunel, Ruoxi Jia, Xin Liu, Lingjuan Lyu, Dawn Song, Chenguang Wang
conference: "Arxiv"
year: 2024
bibkey: tu2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.10557"}
tags: ['Efficiency and Optimization', 'RAG', 'Merging', 'Training Techniques', 'Multimodal Models']
---
We present a novel instruction tuning recipe to improve the zero-shot task
generalization of multimodal large language models. In contrast to existing
instruction tuning mechanisms that heavily rely on visual instructions, our
approach focuses on language-based instruction tuning, offering a distinct and
more training efficient path for multimodal instruction tuning. We evaluate the
performance of the proposed approach on 9 unseen datasets across both language
and vision modalities. Our results show that our language-only instruction
tuning is able to significantly improve the performance of two pretrained
multimodal models based on Llama 2 and Vicuna on those unseen datasets.
Interestingly, the language instruction following ability also helps unlock the
models to follow vision instructions without explicit training. Compared to the
state of the art multimodal instruction tuning approaches that are mainly based
on visual instructions, our language-based method not only achieves superior
performance but also significantly enhances training efficiency. For instance,
the language-only instruction tuning produces competitive average performance
across the evaluated datasets (with even better performance on language
datasets) with significant training efficiency improvements (on average 4x),
thanks to the striking reduction in the need for vision data. With a small
number of visual instructions, this emerging language instruction following
ability transfers well to the unseen vision datasets, outperforming the state
of the art with greater training efficiency.
