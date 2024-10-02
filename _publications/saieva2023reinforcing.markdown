---
layout: publication
title: 'REINFOREST: Reinforcing Semantic Code Similarity For Cross-lingual Code Search Models'
authors: Saieva Anthony, Chakraborty Saikat, Kaiser Gail
conference: "Arxiv"
year: 2023
bibkey: saieva2023reinforcing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03843"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
'This paper introduces a novel code-to-code search technique that enhances the performance of Large Language Models (LLMs) by including both static and dynamic features as well as utilizing both similar and dissimilar examples during training. We present the first-ever code search method that encodes dynamic runtime information during training without the need to execute either the corpus under search or the search query at inference time and the first code search technique that trains on both positive and negative reference samples. To validate the efficacy of our approach, we perform a set of studies demonstrating the capability of enhanced LLMs to perform cross-language code-to-code search. Our evaluation demonstrates that the effectiveness of our approach is consistent across various model architectures and programming languages. We outperform the state-of-the-art cross-language search tool by up to 44.7\&#37;. Moreover, our ablation studies reveal that even a single positive and negative reference sample in the training process results in substantial performance improvements demonstrating both similar and dissimilar references are important parts of code search. Importantly, we show that enhanced well-crafted, fine-tuned models consistently outperform enhanced larger modern LLMs without fine tuning, even when enhancing the largest available LLMs highlighting the importance for open-sourced models. To ensure the reproducibility and extensibility of our research, we present an open-sourced implementation of our tool and training procedures called REINFOREST.'
