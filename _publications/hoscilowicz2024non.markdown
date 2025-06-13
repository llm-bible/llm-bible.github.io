---
layout: publication
title: 'Non-linear Inference Time Intervention: Improving LLM Truthfulness'
authors: Jakub Hoscilowicz, Adam Wiacek, Jan Chojnacki, Adam Cieslak, Leszek Michon, Vitalii Urbanevych, Artur Janicki
conference: "Arxiv"
year: 2024
bibkey: hoscilowicz2024non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18680"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
In this work, we explore LLM's internal representation space to identify
attention heads that contain the most truthful and accurate information. We
further developed the Inference Time Intervention (ITI) framework, which lets
bias LLM without the need for fine-tuning. The improvement manifests in
introducing a non-linear multi-token probing and multi-token intervention:
Non-Linear ITI (NL-ITI), which significantly enhances performance on evaluation
benchmarks. NL-ITI is tested on diverse multiple-choice datasets, including
TruthfulQA, on which we report over 16% relative MC1 (accuracy of model
pointing to the correct answer) improvement with respect to the baseline ITI
results. Moreover, we achieved a 10% relative improvement over the recently
released Truth Forest (TrFf) method that also focused on ITI improvement.
