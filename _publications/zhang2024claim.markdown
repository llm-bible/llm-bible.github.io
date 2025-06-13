---
layout: publication
title: 'A Claim Decomposition Benchmark For Long-form Answer Verification'
authors: Zhihao Zhang, Yixing Fan, Ruqing Zhang, Jiafeng Guo
conference: "Arxiv"
year: 2024
bibkey: zhang2024claim
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12558"}
  - {name: "Code", url: "https://github.com/FBzzh/CACDD"}
tags: ['Few-Shot', 'Reinforcement Learning', 'Fine-Tuning', 'Has Code', 'Applications']
---
The advancement of LLMs has significantly boosted the performance of complex
long-form question answering tasks. However, one prominent issue of LLMs is the
generated "hallucination" responses that are not factual. Consequently,
attribution for each claim in responses becomes a common solution to improve
the factuality and verifiability. Existing researches mainly focus on how to
provide accurate citations for the response, which largely overlook the
importance of identifying the claims or statements for each response. To bridge
this gap, we introduce a new claim decomposition benchmark, which requires
building system that can identify atomic and checkworthy claims for LLM
responses. Specifically, we present the Chinese Atomic Claim Decomposition
Dataset (CACDD), which builds on the WebCPM dataset with additional expert
annotations to ensure high data quality. The CACDD encompasses a collection of
500 human-annotated question-answer pairs, including a total of 4956 atomic
claims. We further propose a new pipeline for human annotation and describe the
challenges of this task. In addition, we provide experiment results on
zero-shot, few-shot and fine-tuned LLMs as baselines. The results show that the
claim decomposition is highly challenging and requires further explorations.
All code and data are publicly available at
\url\{https://github.com/FBzzh/CACDD\}.
