---
layout: publication
title: 'An Active Learning Framework For Inclusive Generation By Large Language Models'
authors: Sabit Hassan, Anthony Sicilia, Malihe Alikhani
conference: "Arxiv"
year: 2024
bibkey: hassan2024active
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13641"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Distillation']
---
Ensuring that Large Language Models (LLMs) generate text representative of
diverse sub-populations is essential, particularly when key concepts related to
under-represented groups are scarce in the training data. We address this
challenge with a novel clustering-based active learning framework, enhanced
with knowledge distillation. The proposed framework transforms the intermediate
outputs of the learner model, enabling effective active learning for generative
tasks for the first time. Integration of clustering and knowledge distillation
yields more representative models without prior knowledge of underlying data
distribution and overbearing human efforts. We validate our approach in
practice through case studies in counter-narration and style transfer. We
construct two new datasets in tandem with model training, showing a performance
improvement of 2%-10% over baseline models. Our results also show more
consistent performance across various data subgroups and increased lexical
diversity, underscoring our model's resilience to skewness in available data.
Further, our results show that the data acquired via our approach improves the
performance of secondary models not involved in the learning loop, showcasing
practical utility of the framework.
