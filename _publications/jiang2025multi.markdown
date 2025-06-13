---
layout: publication
title: 'Danmakutppbench: A Multi-modal Benchmark For Temporal Point Process Modeling And Understanding'
authors: Yue Jiang, Jichu Li, Yang Liu, Dingkang Yang, Feng Zhou, Quyu Kong
conference: "Arxiv"
year: 2025
bibkey: jiang2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18411"}
  - {name: "Code", url: "https://github.com/FRENKIE-CHIANG/DanmakuTPPBench"}
tags: ['Agentic', 'Has Code', 'Language Modeling', 'Tools']
---
We introduce DanmakuTPPBench, a comprehensive benchmark designed to advance multi-modal Temporal Point Process (TPP) modeling in the era of Large Language Models (LLMs). While TPPs have been widely studied for modeling temporal event sequences, existing datasets are predominantly unimodal, hindering progress in models that require joint reasoning over temporal, textual, and visual information. To address this gap, DanmakuTPPBench comprises two complementary components: (1) DanmakuTPP-Events, a novel dataset derived from the Bilibili video platform, where user-generated bullet comments (Danmaku) naturally form multi-modal events annotated with precise timestamps, rich textual content, and corresponding video frames; (2) DanmakuTPP-QA, a challenging question-answering dataset constructed via a novel multi-agent pipeline powered by state-of-the-art LLMs and multi-modal LLMs (MLLMs), targeting complex temporal-textual-visual reasoning. We conduct extensive evaluations using both classical TPP models and recent MLLMs, revealing significant performance gaps and limitations in current methods' ability to model multi-modal event dynamics. Our benchmark establishes strong baselines and calls for further integration of TPP modeling into the multi-modal language modeling landscape. The code and dataset have been released at https://github.com/FRENKIE-CHIANG/DanmakuTPPBench
