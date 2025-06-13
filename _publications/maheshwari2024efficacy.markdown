---
layout: publication
title: 'Efficacy Of Synthetic Data As A Benchmark'
authors: Gaurav Maheshwari, Dmitry Ivanov, Kevin El Haddad
conference: "Arxiv"
year: 2024
bibkey: maheshwari2024efficacy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11968"}
tags: ['Training Techniques', 'Few-Shot', 'Reinforcement Learning', 'Ethics and Bias', 'Applications']
---
Large language models (LLMs) have enabled a range of applications in
zero-shot and few-shot learning settings, including the generation of synthetic
datasets for training and testing. However, to reliably use these synthetic
datasets, it is essential to understand how representative they are of
real-world data. We investigate this by assessing the effectiveness of
generating synthetic data through LLM and using it as a benchmark for various
NLP tasks. Our experiments across six datasets, and three different tasks, show
that while synthetic data can effectively capture performance of various
methods for simpler tasks, such as intent classification, it falls short for
more complex tasks like named entity recognition. Additionally, we propose a
new metric called the bias factor, which evaluates the biases introduced when
the same LLM is used to both generate benchmarking data and to perform the
tasks. We find that smaller LLMs exhibit biases towards their own generated
data, whereas larger models do not. Overall, our findings suggest that the
effectiveness of synthetic data as a benchmark varies depending on the task,
and that practitioners should rely on data generated from multiple larger
models whenever possible.
