---
layout: publication
title: Preserving Knowledge In Large Language Model With Model45;agnostic Self45;decompression
authors: Zhang Zilun, Sun Yutao, Zhao Tiancheng, Sha Leigang, Xu Ruochen, Lee Kyusong, Yin Jianwei
conference: "Arxiv"
year: 2024
bibkey: zhang2024preserving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11354"}
tags: ['Fine Tuning', 'Multimodal Models', 'Training Techniques']
---
Humans can retain old knowledge while learning new information but Large Language Models (LLMs) often suffer from catastrophic forgetting when post45;pretrained or supervised fine45;tuned (SFT) on domain45;specific data. Moreover for Multimodal Large Language Models (MLLMs) which are composed of the LLM base and visual projector (e.g. LLaVA) a significant decline in performance on language benchmarks was observed compared to their single45;modality counterparts. To address these challenges we introduce a novel model45;agnostic self45;decompression method Tree Generation (TG) that decompresses knowledge within LLMs into the training corpus. This paper focuses on TG45;SFT which can synthetically generate SFT data for the instruction tuning steps. By incorporating the dumped corpus during SFT for MLLMs we significantly reduce the forgetting problem.
