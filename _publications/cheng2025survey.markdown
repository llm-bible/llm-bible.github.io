---
layout: publication
title: 'A Survey On Data Contamination For Large Language Models'
authors: Yuxing Cheng, Yi Chang, Yuan Wu
conference: "Arxiv"
year: 2025
bibkey: cheng2025survey
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14425"}
tags: ['Survey Paper', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques']
---
Recent advancements in Large Language Models (LLMs) have demonstrated significant progress in various areas, such as text generation and code synthesis. However, the reliability of performance evaluation has come under scrutiny due to data contamination-the unintended overlap between training and test datasets. This overlap has the potential to artificially inflate model performance, as LLMs are typically trained on extensive datasets scraped from publicly available sources. These datasets often inadvertently overlap with the benchmarks used for evaluation, leading to an overestimation of the models' true generalization capabilities. In this paper, we first examine the definition and impacts of data contamination. Secondly, we review methods for contamination-free evaluation, focusing on three strategies: data updating-based methods, data rewriting-based methods, and prevention-based methods. Specifically, we highlight dynamic benchmarks and LLM-driven evaluation methods. Finally, we categorize contamination detecting methods based on model information dependency: white-Box, gray-Box, and black-Box detection approaches. Our survey highlights the requirements for more rigorous evaluation protocols and proposes future directions for addressing data contamination challenges.
