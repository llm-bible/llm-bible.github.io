---
layout: publication
title: 'Encoder-decoder Gemma: Improving The Quality-efficiency Trade-off Via Adaptation'
authors: Biao Zhang, Fedor Moiseev, Joshua Ainslie, Paul Suganthan, Min Ma, Surya Bhupatiraju, Fede Lebron, Orhan Firat, Armand Joulin, Zhe Dong
conference: "Arxiv"
year: 2025
bibkey: zhang2025encoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06225"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
While decoder-only large language models (LLMs) have shown impressive
results, encoder-decoder models are still widely adopted in real-world
applications for their inference efficiency and richer encoder representation.
In this paper, we study a novel problem: adapting pretrained decoder-only LLMs
to encoder-decoder, with the goal of leveraging the strengths of both
approaches to achieve a more favorable quality-efficiency trade-off. We argue
that adaptation not only enables inheriting the capability of decoder-only LLMs
but also reduces the demand for computation compared to pretraining from
scratch. We rigorously explore different pretraining objectives and parameter
initialization/optimization techniques. Through extensive experiments based on
Gemma 2 (2B and 9B) and a suite of newly pretrained mT5-sized models (up to
1.6B), we demonstrate the effectiveness of adaptation and the advantage of
encoder-decoder LLMs. Under similar inference budget, encoder-decoder LLMs
achieve comparable (often better) pretraining performance but substantially
better finetuning performance than their decoder-only counterpart. For example,
Gemma 2B-2B outperforms Gemma 2B by \\(\sim\\)7% after instruction tuning.
Encoder-decoder adaptation also allows for flexible combination of
different-sized models, where Gemma 9B-2B significantly surpasses Gemma 2B-2B
by \\(>\\)3%. The adapted encoder representation also yields better results on
SuperGLUE. We will release our checkpoints to facilitate future research.
