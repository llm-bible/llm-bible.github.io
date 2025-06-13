---
layout: publication
title: 'Thinkedit: Interpretable Weight Editing To Mitigate Overly Short Thinking In Reasoning Models'
authors: Chung-en Sun, Ge Yan, Tsui-wei Weng
conference: "Arxiv"
year: 2025
bibkey: sun2025interpretable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22048"}
  - {name: "Code", url: "https://github.com/Trustworthy-ML-Lab/ThinkEdit"}
tags: ['Has Code', 'Model Architecture', 'Attention Mechanism', 'Reinforcement Learning']
---
Recent studies have shown that Large Language Models (LLMs) augmented with
chain-of-thought (CoT) reasoning demonstrate impressive problem-solving
abilities. However, in this work, we identify a recurring issue where these
models occasionally generate overly short reasoning, leading to degraded
performance on even simple mathematical problems. Specifically, we investigate
how reasoning length is embedded in the hidden representations of reasoning
models and its impact on accuracy. Our analysis reveals that reasoning length
is governed by a linear direction in the representation space, allowing us to
induce overly short reasoning by steering the model along this direction.
Building on this insight, we introduce ThinkEdit, a simple yet effective
weight-editing approach to mitigate the issue of overly short reasoning. We
first identify a small subset of attention heads (approximately 2%) that
predominantly drive short reasoning behavior. We then edit the output
projection weights of these heads to suppress the short reasoning direction.
With changes to only 0.1% of the model's parameters, ThinkEdit effectively
reduces overly short reasoning and yields notable accuracy gains for short
reasoning outputs (+5.44%), along with an overall improvement across multiple
math benchmarks (+2.43%). Our findings provide new mechanistic insights into
how reasoning length is controlled within LLMs and highlight the potential of
fine-grained model interventions to improve reasoning quality. Our code is
available at https://github.com/Trustworthy-ML-Lab/ThinkEdit
