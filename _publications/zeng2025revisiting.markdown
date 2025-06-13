---
layout: publication
title: 'Revisiting The Test-time Scaling Of O1-like Models: Do They Truly Possess Test-time Scaling Capabilities?'
authors: Zhiyuan Zeng, Qinyuan Cheng, Zhangyue Yin, Yunhua Zhou, Xipeng Qiu
conference: "Arxiv"
year: 2025
bibkey: zeng2025revisiting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12215'}
tags: ['RAG']
---
The advent of test-time scaling in large language models (LLMs), exemplified
by OpenAI's o1 series, has advanced reasoning capabilities by scaling
computational resource allocation during inference. While successors like QwQ,
Deepseek-R1 (R1) and LIMO replicate these advancements, whether these models
truly possess test-time scaling capabilities remains underexplored. This study
found that longer CoTs of these o1-like models do not consistently enhance
accuracy; in fact, correct solutions are often shorter than incorrect ones for
the same questions. Further investigation shows this phenomenon is closely
related to models' self-revision capabilities - longer CoTs contain more
self-revisions, which often lead to performance degradation. We then compare
sequential and parallel scaling strategies on QwQ, R1 and LIMO, finding that
parallel scaling achieves better coverage and scalability. Based on these
insights, we propose Shortest Majority Vote, a method that combines parallel
scaling strategies with CoT length characteristics, significantly improving
models' test-time scalability compared to conventional majority voting
approaches.
