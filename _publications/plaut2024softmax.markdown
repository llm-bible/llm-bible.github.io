---
layout: publication
title: Softmax Probabilities (Mostly) Predict Large Language Model Correctness on Multiple-Choice QA
authors: Plaut Benjamin, Nguyen Khanh, Trinh Tu
conference: "Arxiv"
year: 2024
bibkey: plaut2024softmax
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13213"}
tags: ['Ethics And Bias', 'RAG']
---
Although large language models (LLMs) perform impressively on many tasks overconfidence remains a problem. We hypothesized that on multiple-choice QA tasks wrong answers would be associated with smaller maximum softmax probabilities (MSPs) compared to correct answers. We comprehensively evaluate this hypothesis on ten open-source LLMs and five datasets and find strong evidence for our hypothesis among models which perform well on the original QA task. For the six LLMs with the best QA performance the AUROC derived from the MSP was better than random chance with p < 10^-4 in 59/60 instances. Among those six LLMs the average AUROC ranged from 60 to 69. Leveraging these findings we propose a multiple-choice QA task with an option to abstain and show that performance can be improved by selectively abstaining based on the MSP of the initial model response. We also run the same experiments with pre-softmax logits instead of softmax probabilities and find similar (but not identical) results.
