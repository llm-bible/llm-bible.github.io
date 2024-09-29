---
layout: publication
title: LION Empowering Multimodal Large Language Model With Dual45;level Visual Knowledge
authors: Chen Gongwei, Shen Leyang, Shao Rui, Deng Xiang, Nie Liqiang
conference: "Arxiv"
year: 2023
bibkey: chen2023lion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11860"}
tags: ['Multimodal Models', 'Prompting', 'RAG']
---
Multimodal Large Language Models (MLLMs) have endowed LLMs with the ability to perceive and understand multi45;modal signals. However most of the existing MLLMs mainly adopt vision encoders pretrained on coarsely aligned image45;text pairs leading to insufficient extraction and reasoning of visual knowledge. To address this issue we devise a dual45;Level vIsual knOwledge eNhanced Multimodal Large Language Model (LION) which empowers the MLLM by injecting visual knowledge in two levels. 1) Progressive incorporation of fine45;grained spatial45;aware visual knowledge. We design a vision aggregator cooperated with region45;level vision45;language (VL) tasks to incorporate fine45;grained spatial45;aware visual knowledge into the MLLM. To alleviate the conflict between image45;level and region45;level VL tasks during incorporation we devise a dedicated stage45;wise instruction45;tuning strategy with mixture45;of45;adapters. This progressive incorporation scheme contributes to the mutual promotion between these two kinds of VL tasks. 2) Soft prompting of high45;level semantic visual evidence. We facilitate the MLLM with high45;level semantic visual evidence by leveraging diverse image tags. To mitigate the potential influence caused by imperfect predicted tags we propose a soft prompting method by embedding a learnable token into the tailored text instruction. Comprehensive experiments on several multi45;modal benchmarks demonstrate the superiority of our model (e.g. improvement of 537; accuracy on VSR and 337; CIDEr on TextCaps over InstructBLIP 537; accuracy on RefCOCOg over Kosmos45;2).
