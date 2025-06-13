---
layout: publication
title: 'Does Data Contamination Detection Work (well) For Llms? A Survey And Evaluation On Detection Assumptions'
authors: Yujuan Fu, Ozlem Uzuner, Meliha Yetisgen, Fei Xia
conference: "Arxiv"
year: 2024
bibkey: fu2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18966"}
tags: ['Security', 'Training Techniques', 'Survey Paper', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated great performance across various benchmarks, showing potential as general-purpose task solvers. However, as LLMs are typically trained on vast amounts of data, a significant concern in their evaluation is data contamination, where overlap between training data and evaluation datasets inflates performance assessments. Multiple approaches have been developed to identify data contamination. These approaches rely on specific assumptions that may not hold universally across different settings. To bridge this gap, we systematically review 50 papers on data contamination detection, categorize the underlying assumptions, and assess whether they have been rigorously validated. We identify and analyze eight categories of assumptions and test three of them as case studies. Our case studies focus on detecting direct, instance-level data contamination, which is also referred to as Membership Inference Attacks (MIA). Our analysis reveals that MIA approaches based on these three assumptions can have similar performance to random guessing, on datasets used in LLM pretraining, suggesting that current LLMs might learn data distributions rather than memorizing individual instances. Meanwhile, MIA can easily fail when there are data distribution shifts between the seen and unseen instances.
