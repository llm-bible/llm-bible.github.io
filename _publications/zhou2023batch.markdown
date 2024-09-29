---
layout: publication
title: Batch Calibration Rethinking Calibration For In45;context Learning And Prompt Engineering
authors: Zhou Han, Wan Xingchen, Proleev Lev, Mincu Diana, Chen Jilin, Heller Katherine, Roy Subhrajit
conference: "Arxiv"
year: 2023
bibkey: zhou2023batch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17249"}
tags: ['Applications', 'Ethics And Bias', 'Prompting']
---
Prompting and in45;context learning (ICL) have become efficient learning paradigms for large language models (LLMs). However LLMs suffer from prompt brittleness and various bias factors in the prompt including but not limited to the formatting the choice verbalizers and the ICL examples. To address this problem that results in unexpected performance degradation calibration methods have been developed to mitigate the effects of these biases while recovering LLM performance. In this work we first conduct a systematic analysis of the existing calibration methods where we both provide a unified view and reveal the failure cases. Inspired by these analyses we propose Batch Calibration (BC) a simple yet intuitive method that controls the contextual bias from the batched input unifies various prior approaches and effectively addresses the aforementioned issues. BC is zero45;shot inference45;only and incurs negligible additional costs. In the few45;shot setup we further extend BC to allow it to learn the contextual bias from labeled data. We validate the effectiveness of BC with PaLM 245;(S M L) and CLIP models and demonstrate state45;of45;the45;art performance over previous calibration baselines across more than 10 natural language understanding and image classification tasks.
