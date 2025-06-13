---
layout: publication
title: 'Proreason: Multi-modal Proactive Reasoning With Decoupled Eyesight And Wisdom'
authors: Jingqi Zhou, Sheng Wang, Jingwei Dong, Kai Liu, Lei Li, Jiahui Gao, Jiyue Jiang, Lingpeng Kong, Chuan Wu
conference: "Arxiv"
year: 2024
bibkey: zhou2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14138'}
tags: ['RAG', 'Multimodal Models', 'Tools']
---
Large vision-language models (LVLMs) have witnessed significant progress on visual understanding tasks. However, they often prioritize language knowledge over image information on visual reasoning tasks, incurring performance degradation. To tackle this issue, we first identify the drawbacks of existing solutions (i.e., limited multi-modal reasoning capacities, and insufficient and irrelevant visual descriptions). We then decompose visual reasoning process into two stages: proactive visual perception (i.e., eyesight) and textual reasoning (i.e., wisdom), and introduce a novel visual reasoning framework named ProReason. This framework features decoupled vision-reasoning capabilities and multi-run proactive perception. Briefly, given a multi-modal question, ProReason iterates proactive information collection and reasoning until the answer can be concluded with necessary and sufficient visual descriptions. Notably, the disassociation of capabilities allows seamless integration of existing large language models (LLMs) to compensate for the reasoning deficits of LVLMs. Our extensive experiments demonstrate that ProReason outperforms existing multi-step reasoning frameworks on various benchmarks for both open-source and closed-source models, with the average performance gain reaching 13.2%. Besides, the integration of LLMs allows ProReason to produce high-quality visual reasoning data, which empowers ProReason-distilled models (i.e., ProReason-VL and ProReason-Q3) to achieve superior performance in downstream tasks. Our insights into existing solutions and the decoupled perspective for feasible integration of LLMs illuminate future research on visual reasoning techniques, especially LLM-assisted ones.
