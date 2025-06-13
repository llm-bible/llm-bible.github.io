---
layout: publication
title: 'Training Domain Draft Models For Speculative Decoding: Best Practices And Insights'
authors: Fenglu Hong, Ravi Raju, Jonathan Lingjie Li, Bo Li, Urmish Thakker, Avinash Ravichandran, Swayambhoo Jain, Changran Hu
conference: "Arxiv"
year: 2025
bibkey: hong2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07807"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Distillation']
---
Speculative decoding is an effective method for accelerating inference of
large language models (LLMs) by employing a small draft model to predict the
output of a target model. However, when adapting speculative decoding to
domain-specific target models, the acceptance rate of the generic draft model
drops significantly due to domain shift. In this work, we systematically
investigate knowledge distillation techniques for training domain draft models
to improve their speculation accuracy. We compare white-box and black-box
distillation approaches and explore their effectiveness in various data
accessibility scenarios, including historical user queries, curated domain
data, and synthetically generated alignment data. Our experiments across
Function Calling, Biology, and Chinese domains show that offline distillation
consistently outperforms online distillation by 11% to 25%, white-box
distillation surpasses black-box distillation by 2% to 10%, and data scaling
trends hold across domains. Additionally, we find that synthetic data can
effectively align draft models and achieve 80% to 93% of the performance of
training on historical user queries. These findings provide practical
guidelines for training domain-specific draft models to improve speculative
decoding efficiency.
