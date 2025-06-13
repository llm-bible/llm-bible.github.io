---
layout: publication
title: 'Quantifying Contamination In Evaluating Code Generation Capabilities Of Language Models'
authors: Martin Riddell, Ansong Ni, Arman Cohan
conference: "Arxiv"
year: 2024
bibkey: riddell2024quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04811"}
tags: ['Security', 'Training Techniques', 'Survey Paper', 'Reinforcement Learning', 'Pretraining Methods', 'Applications']
---
While large language models have achieved remarkable performance on various
code generation benchmarks, there have been growing concerns regarding
potential contamination of these benchmarks as they may be leaked into
pretraining and finetuning data. While recent work has investigated
contamination in natural language generation and understanding tasks, there has
been less extensive research into how data contamination impacts the evaluation
of code generation, which is critical for understanding the robustness and
reliability of LLMs in programming contexts. In this work, we perform a
comprehensive study of data contamination of popular code generation
benchmarks, and precisely quantify their overlap with pretraining corpus
through both surface-level and semantic-level matching. In our experiments, we
show that there are substantial overlap between popular code generation
benchmarks and open training corpus, and models perform significantly better on
the subset of the benchmarks where similar solutions are seen during training.
We also conduct extensive analysis on the factors that affects model
memorization and generalization, such as model size, problem difficulty, and
question length. We release all resulting files from our matching pipeline for
future research.
