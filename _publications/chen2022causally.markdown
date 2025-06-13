---
layout: publication
title: 'Causally Testing Gender Bias In Llms: A Case Study On Occupational Bias'
authors: Yuen Chen, Vethavikashini Chithrra Raghuram, Justus Mattern, Rada Mihalcea, Zhijing Jin
conference: "Arxiv"
year: 2022
bibkey: chen2022causally
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.10678'}
  - {name: "Code", url: 'https://github.com/chenyuen0103/gender-bias'}
tags: ['Has Code', 'Tools', 'Prompting', 'Bias Mitigation', 'Ethics and Bias']
---
Generated texts from large language models (LLMs) have been shown to exhibit
a variety of harmful, human-like biases against various demographics. These
findings motivate research efforts aiming to understand and measure such
effects. This paper introduces a causal formulation for bias measurement in
generative language models. Based on this theoretical foundation, we outline a
list of desiderata for designing robust bias benchmarks. We then propose a
benchmark called OccuGender, with a bias-measuring procedure to investigate
occupational gender bias. We test several state-of-the-art open-source LLMs on
OccuGender, including Llama, Mistral, and their instruction-tuned versions. The
results show that these models exhibit substantial occupational gender bias.
Lastly, we discuss prompting strategies for bias mitigation and an extension of
our causal formulation to illustrate the generalizability of our framework. Our
code and data https://github.com/chenyuen0103/gender-bias.
