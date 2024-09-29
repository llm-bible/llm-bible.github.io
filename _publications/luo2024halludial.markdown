---
layout: publication
title: Halludial A Large-scale Benchmark For Automatic Dialogue-level Hallucination Evaluation
authors: Luo Wen, Shen Tianshu, Li Wei, Peng Guangyue, Xuan Richeng, Wang Houfeng, Yang Xi
conference: "Arxiv"
year: 2024
bibkey: luo2024halludial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07070"}
  - {name: "Code", url: "https://github.com/FlagOpen/HalluDial"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Large Language Models (LLMs) have significantly advanced the field of Natural Language Processing (NLP) achieving remarkable performance across diverse tasks and enabling widespread real-world applications. However LLMs are prone to hallucination generating content that either conflicts with established knowledge or is unfaithful to the original sources. Existing hallucination benchmarks primarily focus on sentence- or passage-level hallucination detection neglecting dialogue-level evaluation hallucination localization and rationale provision. They also predominantly target factuality hallucinations while underestimating faithfulness hallucinations often relying on labor-intensive or non-specialized evaluators. To address these limitations we propose HalluDial the first comprehensive large-scale benchmark for automatic dialogue-level hallucination evaluation. HalluDial encompasses both spontaneous and induced hallucination scenarios covering factuality and faithfulness hallucinations. The benchmark includes 4094 dialogues with a total of 146856 samples. Leveraging HalluDial we conduct a comprehensive meta-evaluation of LLMs hallucination evaluation capabilities in information-seeking dialogues and introduce a specialized judge language model HalluJudge. The high data quality of HalluDial enables HalluJudge to achieve superior or competitive performance in hallucination evaluation facilitating the automatic assessment of dialogue-level hallucinations in LLMs and providing valuable insights into this phenomenon. The dataset and the code are available at https://github.com/FlagOpen/HalluDial.
