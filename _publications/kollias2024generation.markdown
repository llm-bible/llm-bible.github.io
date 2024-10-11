---
layout: publication
title: 'Generation Constraint Scaling Can Mitigate Hallucination'
authors: Kollias Georgios, Das Payel, Chaudhury Subhajit
conference: "Arxiv"
year: 2024
bibkey: kollias2024generation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16908"}
tags: ['Training Techniques', 'Uncategorized']
---
Addressing the issue of hallucinations in large language models (LLMs) is a critical challenge. As the cognitive mechanisms of hallucination have been related to memory, here we explore hallucination for LLM that is enabled with explicit memory mechanisms. We empirically demonstrate that by simply scaling the readout vector that constrains generation in a memory-augmented LLM decoder, hallucination mitigation can be achieved in a training-free manner. Our method is geometry-inspired and outperforms a state-of-the-art LLM editing method on the task of generation of Wikipedia-like biography entries both in terms of generation quality and runtime complexity.
