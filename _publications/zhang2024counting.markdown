---
layout: publication
title: 'Counting Ability Of Large Language Models And Impact Of Tokenization'
authors: Xiang Zhang, Juntai Cao, Chenyu You
conference: "Arxiv"
year: 2024
bibkey: zhang2024counting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.19730'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods']
---
Transformers, the backbone of modern large language models (LLMs), face
inherent architectural limitations that impede their reasoning capabilities.
Unlike recurrent networks, Transformers lack recurrent connections, confining
them to constant-depth computation. This restriction places them in the
complexity class TC\\(^0\\), making them theoretically incapable of solving tasks
that demand increasingly deep reasoning as input length grows. Counting, a
fundamental component of many reasoning tasks, also requires reasoning depth to
grow linearly to be performed inductively. While previous studies have
established the upper limits of counting ability in Transformer-based expert
models (i.e., models specifically trained for counting tasks), these findings
do not directly extend to general-purpose LLMs due to differences in reasoning
mechanisms. Recent work has highlighted how Chain of Thought (CoT) reasoning
can help alleviate some of the architectural limitations of Transformers in
counting tasks. However, little attention has been paid to the role of
tokenization in these models. Unlike expert models that often use
character-level tokenization, LLMs typically rely on byte-level (BPE)
tokenizers, which fundamentally alters the way reasoning is processed. Our work
investigates the impact of tokenization on the counting abilities of LLMs,
uncovering substantial performance variations based on input tokenization
differences. We provide both theoretical and experimental analyses, offering
insights into how tokenization choices can undermine models' theoretical
computability, thereby inspiring the design of new tokenization methods to
enhance reasoning in LLMs.
