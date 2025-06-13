---
layout: publication
title: 'Teaching Language Models To Critique Via Reinforcement Learning'
authors: Zhihui Xie, Jie Chen, Liyu Chen, Weichao Mao, Jingjing Xu, Lingpeng Kong
conference: "Arxiv"
year: 2025
bibkey: xie2025teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03492"}
tags: ['Tools', 'Agentic', 'Applications', 'Reinforcement Learning']
---
Teaching large language models (LLMs) to critique and refine their outputs is
crucial for building systems that can iteratively improve, yet it is
fundamentally limited by the ability to provide accurate judgments and
actionable suggestions. In this work, we study LLM critics for code generation
and propose \\(\texttt\{CTRL\}\\), a framework for \\(\texttt\{C\}\\)ritic
\\(\texttt\{T\}\\)raining via \\(\texttt\{R\}\\)einforcement \\(\texttt\{L\}\\)earning, which
trains a critic model to generate feedback that maximizes correction
performance for a fixed generator model without human supervision. Our results
demonstrate that critics trained with \\(\texttt\{CTRL\}\\) significantly enhance
pass rates and mitigate compounding errors across both base and stronger
generator models. Furthermore, we show that these critic models act as accurate
generative reward models and enable test-time scaling through iterative
critique-revision, achieving up to 106.1% relative improvements across
challenging code generation benchmarks.
