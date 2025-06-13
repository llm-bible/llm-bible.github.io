---
layout: publication
title: 'Meta-reflection: A Feedback-free Reflection Learning Framework'
authors: Yaoke Wang, Yun Zhu, Xintong Bao, Wenqiao Zhang, Suyang Dai, Kehan Chen, Wenqiang Li, Gang Huang, Siliang Tang, Yueting Zhuang
conference: "Arxiv"
year: 2024
bibkey: wang2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13781"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Reinforcement Learning']
---
Despite the remarkable capabilities of large language models (LLMs) in
natural language understanding and reasoning, they often display undesirable
behaviors, such as generating hallucinations and unfaithful reasoning. A
prevalent strategy to mitigate these issues is the use of reflection, which
refines responses through an iterative process. However, while promising,
reflection heavily relies on high-quality external feedback and requires
iterative multi-agent inference processes, thus hindering its practical
application. In this paper, we propose Meta-Reflection, a novel feedback-free
reflection mechanism that necessitates only a single inference pass without
external feedback. Motivated by the human ability to remember and retrieve
reflections from past experiences when encountering similar problems,
Meta-Reflection integrates reflective insights into a codebook, allowing the
historical insights to be stored, retrieved, and used to guide LLMs in
problem-solving. To thoroughly investigate and evaluate the practicality of
Meta-Reflection in real-world scenarios, we introduce an industrial e-commerce
benchmark named E-commerce Customer Intent Detection (ECID). Extensive
experiments conducted on both public datasets and the ECID benchmark highlight
the effectiveness and efficiency of our proposed approach.
