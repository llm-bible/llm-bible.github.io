---
layout: publication
title: 'A Simple Yet Efficient Ensemble Approach For Ai-generated Text Detection'
authors: Harika Abburi, Kalyani Roy, Michael Suesserman, Nirmala Pudota, Balaji Veeramani, Edward Bowen, Sanmitra Bhattacharya
conference: "Arxiv"
year: 2023
bibkey: abburi2023simple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.03084'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Merging', 'Pretraining Methods']
---
Recent Large Language Models (LLMs) have demonstrated remarkable capabilities
in generating text that closely resembles human writing across wide range of
styles and genres. However, such capabilities are prone to potential abuse,
such as fake news generation, spam email creation, and misuse in academic
assignments. Hence, it is essential to build automated approaches capable of
distinguishing between artificially generated text and human-authored text. In
this paper, we propose a simple yet efficient solution to this problem by
ensembling predictions from multiple constituent LLMs. Compared to previous
state-of-the-art approaches, which are perplexity-based or uses ensembles with
a number of LLMs, our condensed ensembling approach uses only two constituent
LLMs to achieve comparable performance. Experiments conducted on four benchmark
datasets for generative text classification show performance improvements in
the range of 0.5 to 100% compared to previous state-of-the-art approaches. We
also study the influence that the training data from individual LLMs have on
model performance. We found that substituting commercially-restrictive
Generative Pre-trained Transformer (GPT) data with data generated from other
open language models such as Falcon, Large Language Model Meta AI (LLaMA2), and
Mosaic Pretrained Transformers (MPT) is a feasible alternative when developing
generative text detectors. Furthermore, to demonstrate zero-shot
generalization, we experimented with an English essays dataset, and results
suggest that our ensembling approach can handle new data effectively.
