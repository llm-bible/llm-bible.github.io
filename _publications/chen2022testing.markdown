---
layout: publication
title: "Testing Occupational Gender Bias In Language Models: Towards Robust Measurement And Zero-shot Debiasing"
authors: Chen Yuen, Raghuram Vethavikashini Chithrra, Mattern Justus, Sachan Mrinmaya, Mihalcea Rada, Schölkopf Bernhard, Jin Zhijing
conference: "Arxiv"
year: 2022
bibkey: chen2022testing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10678"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Generated texts from large language models (LLMs) have been shown to exhibit a variety of harmful human-like biases against various demographics. These findings motivate research efforts aiming to understand and measure such effects. Prior works have proposed benchmarks for identifying and techniques for mitigating these stereotypical associations. However as recent research pointed out existing benchmarks lack a robust experimental setup hindering the inference of meaningful conclusions from their evaluation metrics. In this paper we introduce a list of desiderata for robustly measuring biases in generative language models. Building upon these design principles we propose a benchmark called OCCUGENDER with a bias-measuring procedure to investigate occupational gender bias. We then use this benchmark to test several state-of-the-art open-source LLMs including Llama Mistral and their instruction-tuned versions. The results show that these models exhibit substantial occupational gender bias. We further propose prompting techniques to mitigate these biases without requiring fine-tuning. Finally we validate the effectiveness of our methods through experiments on the same set of models.
