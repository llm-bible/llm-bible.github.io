---
layout: publication
title: 'Research: Learning To Reason With Search For Llms Via Reinforcement Learning'
authors: Mingyang Chen, Tianpeng Li, Haoze Sun, Yijie Zhou, Chenzheng Zhu, Haofen Wang, Jeff Z. Pan, Wen Zhang, Huajun Chen, Fan Yang, Zenan Zhou, Weipeng Chen
conference: "Arxiv"
year: 2025
bibkey: chen2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19470"}
tags: ['Tools', 'Agentic', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown remarkable capabilities in reasoning,
exemplified by the success of OpenAI-o1 and DeepSeek-R1. However, integrating
reasoning with external search processes remains challenging, especially for
complex multi-hop questions requiring multiple retrieval steps. We propose
ReSearch, a novel framework that trains LLMs to Reason with Search via
reinforcement learning without using any supervised data on reasoning steps.
Our approach treats search operations as integral components of the reasoning
chain, where when and how to perform searches is guided by text-based thinking,
and search results subsequently influence further reasoning. We train ReSearch
on Qwen2.5-7B(-Instruct) and Qwen2.5-32B(-Instruct) models and conduct
extensive experiments. Despite being trained on only one dataset, our models
demonstrate strong generalizability across various benchmarks. Analysis reveals
that ReSearch naturally elicits advanced reasoning capabilities such as
reflection and self-correction during the reinforcement learning process.
