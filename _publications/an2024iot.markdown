---
layout: publication
title: 'Iot-llm: Enhancing Real-world Iot Task Reasoning With Large Language Models'
authors: Tuo An, Yunjiao Zhou, Han Zou, Jianfei Yang
conference: "Arxiv"
year: 2024
bibkey: an2024iot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02429"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) excel in textual and visual tasks but often produce outputs that defy physical laws when dealing with physical-world reasoning tasks. Inspired by human cognition, where perception is fundamental to reasoning, we explore augmenting LLMs with enhanced perception abilities using Internet of Things (IoT) sensor data and pertinent knowledge for IoT-sensory task reasoning in the physical world. In this work, we systematically study LLMs' capability to address real-world IoT-sensory tasks by augmenting their perception and knowledge base, and then propose a unified framework, IoT-LLM, to enhance such capability. In IoT-LLM, we customize three steps for LLMs: preprocessing IoT data into formats amenable to LLMs, expanding their understanding via IoT-oriented retrieval-augmented generation based on in-context learning and activating their commonsense knowledge through chain-of-thought prompting and specialized role definitions. We design a new benchmark comprising five real-world tasks with varying data types and reasoning complexities to evaluate the performance of IoT-LLM. Experimental results on six LLMs reveal that IoT-LLM significantly improves the performance of IoT-sensory task reasoning of LLMs, with models like GPT-4o-mini showing a 49.4% average improvement over previous methods.
