---
layout: publication
title: 'Jumpcoder: Go Beyond Autoregressive Coder Via Online Modification'
authors: Chen Mouxiang, Tian Hao, Liu Zhongxin, Ren Xiaoxue, Sun Jianling
conference: "Arxiv"
year: 2024
bibkey: chen2024go
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07870"}
  - {name: "Code", url: "https://github.com/Keytoyze/JumpCoder"}
tags: ['Applications', 'GPT', 'Has Code', 'Pretraining Methods', 'Tools']
---
While existing code large language models (code LLMs) exhibit impressive capabilities in code generation, their autoregressive sequential generation inherently lacks reversibility. This limitation hinders them from timely correcting previous missing statements during coding as humans do, often leading to error propagation and suboptimal performance. We introduce JumpCoder, a novel model-agnostic framework that enables human-like online modification and non-sequential generation to augment code LLMs. The key idea behind JumpCoder is to insert new code into the currently generated code when necessary during generation, which is achieved through an auxiliary infilling model that works in tandem with the code LLM. Since identifying the best infill position beforehand is intractable, we adopt an \textit\{infill-first, judge-later\} strategy, which experiments with filling at the \(k\) most critical positions following the generation of each line, and uses an Abstract Syntax Tree (AST) parser alongside the Generation Model Scoring to effectively judge the validity of each potential infill. Extensive experiments using six state-of-the-art code LLMs across multiple and multilingual benchmarks consistently indicate significant improvements over all baselines. Our code is public at https://github.com/Keytoyze/JumpCoder.
