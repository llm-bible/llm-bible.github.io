---
layout: publication
title: 'Gcot: Chain-of-thought Prompt Learning For Graphs'
authors: Xingtong Yu, Chang Zhou, Zhongwei Kuai, Xinming Zhang, Yuan Fang
conference: "Arxiv"
year: 2025
bibkey: yu2025chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08092"}
tags: ['Tools', 'Prompting']
---
Chain-of-thought (CoT) prompting has achieved remarkable success in natural language processing (NLP). However, its vast potential remains largely unexplored for graphs. This raises an interesting question: How can we design CoT prompting for graphs to guide graph models to learn step by step? On one hand, unlike natural languages, graphs are non-linear and characterized by complex topological structures. On the other hand, many graphs lack textual data, making it difficult to formulate language-based CoT prompting. In this work, we propose the first CoT prompt learning framework for text-free graphs, GCoT. Specifically, we decompose the adaptation process for each downstream task into a series of inference steps, with each step consisting of prompt-based inference, ``thought'' generation, and thought-conditioned prompt learning. While the steps mimic CoT prompting in NLP, the exact mechanism differs significantly. Specifically, at each step, an input graph, along with a prompt, is first fed into a pre-trained graph encoder for prompt-based inference. We then aggregate the hidden layers of the encoder to construct a ``thought'', which captures the working state of each node in the current step. Conditioned on this thought, we learn a prompt specific to each node based on the current state. These prompts are fed into the next inference step, repeating the cycle. To evaluate and analyze the effectiveness of GCoT, we conduct comprehensive experiments on eight public datasets, which demonstrate the advantage of our approach.
