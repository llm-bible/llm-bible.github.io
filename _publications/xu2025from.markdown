---
layout: publication
title: 'From 128K To 4M: Efficient Training Of Ultra-long Context Large Language Models'
authors: Chejian Xu, Wei Ping, Peng Xu, Zihan Liu, Boxin Wang, Mohammad Shoeybi, Bo Li, Bryan Catanzaro
conference: "Arxiv"
year: 2025
bibkey: xu2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06214"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Prompting', 'Applications', 'In-Context Learning']
---
Long-context capabilities are essential for a wide range of applications,
including document and video understanding, in-context learning, and
inference-time scaling, all of which require models to process and reason over
long sequences of text and multimodal data. In this work, we introduce a
efficient training recipe for building ultra-long context LLMs from aligned
instruct model, pushing the boundaries of context lengths from 128K to 1M, 2M,
and 4M tokens. Our approach leverages efficient continued pretraining
strategies to extend the context window and employs effective instruction
tuning to maintain the instruction-following and reasoning abilities. Our
UltraLong-8B, built on Llama3.1-Instruct with our recipe, achieves
state-of-the-art performance across a diverse set of long-context benchmarks.
Importantly, models trained with our approach maintain competitive performance
on standard benchmarks, demonstrating balanced improvements for both long and
short context tasks. We further provide an in-depth analysis of key design
choices, highlighting the impacts of scaling strategies and data composition.
Our findings establish a robust framework for efficiently scaling context
lengths while preserving general model capabilities. We release all model
weights at: https://ultralong.github.io/.
