---
layout: publication
title: Generating Unseen Code Tests In Infinitum
authors: Zalmanovici Marcel, Raz Orna, Farchi Eitan, Freund Iftach
conference: "Arxiv"
year: 2024
bibkey: zalmanovici2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19772"}
tags: ['Applications', 'Training Techniques']
---
Large Language Models (LLMs) are used for many tasks including those related to coding. An important aspect of being able to utilize LLMs is the ability to assess their fitness for specific usages. The common practice is to evaluate LLMs against a set of benchmarks. While benchmarks provide a sound foundation for evaluation and comparison of alternatives they suffer from the well45;known weakness of leaking into the training data cite123;Xu2024Benchmarking125;. We present a method for creating benchmark variations that generalize across coding tasks and programming languages and may also be applied to in45;house code bases. Our approach enables ongoing generation of test45;data thus mitigating the leaking into the training data issue. We implement one benchmark called textit123;auto45;regression125; for the task of text45;to45;code generation in Python. Auto45;regression is specifically created to aid in debugging and in tracking model generation changes as part of the LLM regression testing process.
