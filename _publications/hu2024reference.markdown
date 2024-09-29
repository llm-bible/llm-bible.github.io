---
layout: publication
title: Refchecker Reference45;based Fine45;grained Hallucination Checker And Benchmark For Large Language Models
authors: Hu Xiangkun, Ru Dongyu, Qiu Lin, Guo Qipeng, Zhang Tianhang, Xu Yang, Luo Yun, Liu Pengfei, Zhang Yue, Zhang Zheng
conference: "Arxiv"
year: 2024
bibkey: hu2024reference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14486"}
  - {name: "Code", url: "https://github.com/amazon&#45;science/RefChecker"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have shown impressive capabilities but also a concerning tendency to hallucinate. This paper presents RefChecker a framework that introduces claim45;triplets to represent claims in LLM responses aiming to detect fine45;grained hallucinations. In RefChecker an extractor generates claim45;triplets from a response which are then evaluated by a checker against a reference. We delineate three task settings Zero Noisy and Accurate Context to reflect various real45;world use cases. We curated a benchmark spanning various NLP tasks and annotated 11k claim45;triplets from 2.1k responses by seven LLMs. RefChecker supports both proprietary and open45;source models as the extractor and checker. Experiments demonstrate that claim45;triplets enable superior hallucination detection compared to other granularities such as response sentence and sub45;sentence level claims. RefChecker outperforms prior methods by 6.8 to 26.1 points on our benchmark and the checking results of RefChecker are strongly aligned with human judgments. This work is open sourced at https://github.com/amazon&#45;science/RefChecker
