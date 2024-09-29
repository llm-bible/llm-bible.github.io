---
layout: publication
title: LION Empowering Multimodal Large Language Model with Dual-Level Visual Knowledge
authors: Chen Gongwei, Shen Leyang, Shao Rui, Deng Xiang, Nie Liqiang
conference: "Arxiv"
year: 2023
bibkey: chen2023lion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11860"}
tags: ['Fine Tuning', 'Multimodal Models', 'Prompting', 'RAG']
---
Multimodal Large Language Models (MLLMs) have endowed LLMs with the ability to perceive and understand multi-modal signals. However most of the existing MLLMs mainly adopt vision encoders pretrained on coarsely aligned image-text pairs leading to insufficient extraction and reasoning of visual knowledge. To address this issue we devise a dual-Level vIsual knOwledge eNhanced Multimodal Large Language Model (LION) which empowers the MLLM by injecting visual knowledge in two levels. 1) Progressive incorporation of fine-grained spatial-aware visual knowledge. We design a vision aggregator cooperated with region-level vision-language (VL) tasks to incorporate fine-grained spatial-aware visual knowledge into the MLLM. To alleviate the conflict between image-level and region-level VL tasks during incorporation we devise a dedicated stage-wise instruction-tuning strategy with mixture-of-adapters. This progressive incorporation scheme contributes to the mutual promotion between these two kinds of VL tasks. 2) Soft prompting of high-level semantic visual evidence. We facilitate the MLLM with high-level semantic visual evidence by leveraging diverse image tags. To mitigate the potential influence caused by imperfect predicted tags we propose a soft prompting method by embedding a learnable token into the tailored text instruction. Comprehensive experiments on several multi-modal benchmarks demonstrate the superiority of our model (e.g. improvement of 5 accuracy on VSR and 3 CIDEr on TextCaps over InstructBLIP 5 accuracy on RefCOCOg over Kosmos-2).
