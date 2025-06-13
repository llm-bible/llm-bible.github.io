---
layout: publication
title: 'Preserving Knowledge In Large Language Model With Model-agnostic Self-decompression'
authors: Zilun Zhang, Yutao Sun, Tiancheng Zhao, Leigang Sha, Ruochen Xu, Kyusong Lee, Jianwei Yin
conference: "Arxiv"
year: 2024
bibkey: zhang2024preserving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11354"}
tags: ['Fine-Tuning', 'Training Techniques', 'Multimodal Models']
---
Humans can retain old knowledge while learning new information, but Large
Language Models (LLMs) often suffer from catastrophic forgetting when
post-pretrained or supervised fine-tuned (SFT) on domain-specific data.
Moreover, for Multimodal Large Language Models (MLLMs) which are composed of
the LLM base and visual projector (e.g. LLaVA), a significant decline in
performance on language benchmarks was observed compared to their
single-modality counterparts. To address these challenges, we introduce a novel
model-agnostic self-decompression method, Tree Generation (TG), that
decompresses knowledge within LLMs into the training corpus. This paper focuses
on TG-SFT, which can synthetically generate SFT data for the instruction tuning
steps. By incorporating the dumped corpus during SFT for MLLMs, we
significantly reduce the forgetting problem.
