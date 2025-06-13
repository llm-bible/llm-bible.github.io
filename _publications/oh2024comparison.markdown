---
layout: publication
title: 'Comparison-based Active Preference Learning For Multi-dimensional Personalization'
authors: Minhyeon Oh, Seungjoon Lee, Jungseul Ok
conference: "Arxiv"
year: 2024
bibkey: oh2024comparison
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00524"}
  - {name: "Code", url: "https://github.com/ml-postech/AMPLe"}
tags: ['Ethics and Bias', 'Efficiency and Optimization', 'Has Code', 'Tools']
---
Large language models (LLMs) have shown remarkable success, but aligning them with human preferences remains a core challenge. As individuals have their own, multi-dimensional preferences, recent studies have explored multi-dimensional personalization, which aims to enable models to generate responses personalized to explicit preferences. However, human preferences are often implicit and thus difficult to articulate, limiting the direct application of this approach. To bridge this gap, we propose Active Multi-dimensional Preference Learning (AMPLe), designed to capture implicit user preferences from interactively collected comparative feedback. Building on Bayesian inference, our work introduces a modified posterior update procedure to mitigate estimation bias and potential noise in comparisons. Also, inspired by generalized binary search, we employ an active query selection strategy to minimize the number of required comparisons by a user. Through theoretical analysis and experiments on language generation tasks, we demonstrate feedback efficiency and effectiveness of our framework in personalizing model responses. Our code is publicly available at https://github.com/ml-postech/AMPLe .
