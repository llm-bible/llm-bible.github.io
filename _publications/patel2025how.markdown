---
layout: publication
title: 'How To Get Your LLM To Generate Challenging Problems For Evaluation'
authors: Arkil Patel, Siva Reddy, Dzmitry Bahdanau
conference: "Arxiv"
year: 2025
bibkey: patel2025how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14678'}
tags: ['Applications', 'Tools']
---
The pace of evolution of Large Language Models (LLMs) necessitates new
approaches for rigorous and comprehensive evaluation. Traditional human
annotation is increasingly impracticable due to the complexities and costs
involved in generating high-quality, challenging problems. In this work, we
introduce CHASE, a unified framework to synthetically generate challenging
problems using LLMs without human involvement. For a given task, our approach
builds a hard problem in a bottom-up manner from simpler components. Moreover,
our framework decomposes the generation process into independently verifiable
sub-tasks, thereby ensuring a high level of quality and correctness. We
implement CHASE to create evaluation benchmarks across three diverse domains:
(1) document-based question answering, (2) repository-level code completion,
and (3) math reasoning. The performance of state-of-the-art LLMs on these
synthetic benchmarks lies in the range of 40-60% accuracy, thereby
demonstrating the effectiveness of our framework at generating challenging
problems. We publicly release our benchmarks and code.
