---
layout: publication
title: 'LINGOLY-TOO: Disentangling Reasoning From Knowledge With Templatised Orthographic Obfuscation'
authors: Jude Khouja, Karolina Korgul, Simi Hellsten, Lingyi Yang, Vlad Neacsu, Harry Mayne, Ryan Kearns, Andrew Bean, Adam Mahdi
conference: "Arxiv"
year: 2025
bibkey: khouja2025lingoly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02972"}
tags: ['Reinforcement Learning']
---
The expanding knowledge and memorisation capacity of frontier language models allows them to solve many reasoning tasks directly by exploiting prior knowledge, leading to inflated estimates of their reasoning abilities. We introduce LINGOLY-TOO, a challenging reasoning benchmark grounded in natural language and designed to counteract the effect of non-reasoning abilities on reasoning estimates. Using linguistically informed rulesets, we permute reasoning problems written in real languages to generate numerous question variations. These permutations preserve the intrinsic reasoning steps required for each solution while reducing the likelihood problems are directly solvable with models' knowledge. Experiments and analyses show that models can circumvent reasoning and answer from prior knowledge. On a metric that rewards consistent reasoning, all models perform poorly and exhibit high variance across question permutations, indicating that Large Language Models' (LLMs) reasoning faculty remains brittle. Overall, results on the benchmark reflect the recent progress of Inference-Time Compute (ITC) models but suggest ample room for further improvement. The benchmark is a step towards better measurement of reasoning abilities of LLMs and offers a cautionary tale on the importance of disentangling reasoning abilities from models' internalised knowledge when developing reasoning benchmarks.
