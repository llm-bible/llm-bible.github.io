---
layout: publication
title: 'Understanding The World''s Museums Through Vision-language Reasoning'
authors: Ada-astrid Balauca, Sanjana Garai, Stefan Balauca, Rasesh Udayakumar Shetty, Naitik Agrawal, Dhwanil Subhashbhai Shah, Yuqian Fu, Xi Wang, Kristina Toutanova, Danda Pani Paudel, Luc Van Gool
conference: "Arxiv"
year: 2024
bibkey: balauca2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01370"}
  - {name: "Code", url: "https://github.com/insait-institute/Museum-65"}
tags: ['Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'Has Code', 'Applications']
---
Museums serve as vital repositories of cultural heritage and historical
artifacts spanning diverse epochs, civilizations, and regions, preserving
well-documented collections. Data reveal key attributes such as age, origin,
material, and cultural significance. Understanding museum exhibits from their
images requires reasoning beyond visual features. In this work, we facilitate
such reasoning by (a) collecting and curating a large-scale dataset of 65M
images and 200M question-answer pairs in the standard museum catalog format for
exhibits from all around the world; (b) training large vision-language models
on the collected dataset; (c) benchmarking their ability on five visual
question answering tasks. The complete dataset is labeled by museum experts,
ensuring the quality as well as the practical significance of the labels. We
train two VLMs from different categories: the BLIP model, with vision-language
aligned embeddings, but lacking the expressive power of large language models,
and the LLaVA model, a powerful instruction-tuned LLM enriched with
vision-language reasoning capabilities. Through exhaustive experiments, we
provide several insights on the complex and fine-grained understanding of
museum exhibits. In particular, we show that some questions whose answers can
often be derived directly from visual features are well answered by both types
of models. On the other hand, questions that require the grounding of the
visual features in repositories of human knowledge are better answered by the
large vision-language models, thus demonstrating their superior capacity to
perform the desired reasoning. Find our dataset, benchmarks, and source code
at: https://github.com/insait-institute/Museum-65
