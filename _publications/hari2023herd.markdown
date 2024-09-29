---
layout: publication
title: Herd Using multiple smaller LLMs to match the performances of proprietary large LLMs via an intelligent composer
authors: Hari Surya Narayanan, Thomson Matt
conference: "Arxiv"
year: 2023
bibkey: hari2023herd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19902"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Currently over a thousand LLMs exist that are multi-purpose and are capable of performing real world tasks including Qamp;A text summarization content generation etc. However accessibility scale and reliability of free models prevents them from being widely deployed in everyday use cases. To address the first two issues of access and scale organisations such as HuggingFace have created model repositories where users have uploaded model weights and quantized versions of models trained using different paradigms as well as model cards describing their training process. While some models report performance on commonly used benchmarks not all do and interpreting the real world impact of trading off performance on a benchmark for model deployment cost is unclear. Here we show that a herd of open source models can match or exceed the performance of proprietary models via an intelligent router. We show that a Herd of open source models is able to match the accuracy of ChatGPT despite being composed of models that are effectively 2.5x smaller. We show that in cases where GPT is not able to answer the query Herd is able to identify a model that can at least 40 of the time.
