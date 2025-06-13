---
layout: publication
title: 'A Simple Yet Effective Training-free Prompt-free Approach To Chinese Spelling Correction Based On Large Language Models'
authors: Houquan Zhou, Zhenghua Li, Bo Zhang, Chen Li, Shaopeng Lai, Ji Zhang, Fei Huang, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: zhou2024simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04027"}
tags: ['Prompting', 'RAG', 'Training Techniques', 'Reinforcement Learning']
---
This work proposes a simple training-free prompt-free approach to leverage
large language models (LLMs) for the Chinese spelling correction (CSC) task,
which is totally different from all previous CSC approaches. The key idea is to
use an LLM as a pure language model in a conventional manner. The LLM goes
through the input sentence from the beginning, and at each inference step,
produces a distribution over its vocabulary for deciding the next token, given
a partial sentence. To ensure that the output sentence remains faithful to the
input sentence, we design a minimal distortion model that utilizes
pronunciation or shape similarities between the original and replaced
characters. Furthermore, we propose two useful reward strategies to address
practical challenges specific to the CSC task. Experiments on five public
datasets demonstrate that our approach significantly improves LLM performance,
enabling them to compete with state-of-the-art domain-general CSC models.
