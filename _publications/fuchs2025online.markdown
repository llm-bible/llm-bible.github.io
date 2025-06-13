---
layout: publication
title: 'Online Gaussian Test-time Adaptation Of Vision-language Models'
authors: Clément Fuchs, Maxime Zanella, Christophe De Vleeschouwer
conference: "Arxiv"
year: 2025
bibkey: fuchs2025online
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.04352'}
  - {name: "Code", url: 'https://github.com/cfuchs2023/OGA'}
tags: ['Attention Mechanism', 'Has Code', 'Few-Shot', 'RAG', 'Model Architecture', 'Tools', 'Multimodal Models', 'Reinforcement Learning']
---
Online test-time adaptation (OTTA) of vision-language models (VLMs) has
recently garnered increased attention to take advantage of data observed along
a stream to improve future predictions. Unfortunately, existing methods rely on
dataset-specific hyperparameters, significantly limiting their adaptability to
unseen tasks. In response, we propose Online Gaussian Adaptation (OGA), a novel
method that models the likelihoods of visual features using Gaussian
distributions and incorporates zero-shot priors into an interpretable Maximum A
Posteriori (MAP) estimation framework with fixed hyper-parameters across all
datasets. We demonstrate that OGA outperforms state-of-the-art methods on most
datasets and runs. Additionally, we show that combining OTTA with popular
few-shot techniques (a practical yet overlooked setting in prior research) is
highly beneficial. Furthermore, our experimental study reveals that common OTTA
evaluation protocols, which average performance over at most three runs per
dataset, are inadequate due to the substantial variability observed across runs
for all OTTA methods. Therefore, we advocate for more rigorous evaluation
practices, including increasing the number of runs and considering additional
quantitative metrics, such as our proposed Expected Tail Accuracy (ETA),
calculated as the average accuracy in the worst 10% of runs. We hope these
contributions will encourage more rigorous and diverse evaluation practices in
the OTTA community. Code is available at https://github.com/cfuchs2023/OGA .
