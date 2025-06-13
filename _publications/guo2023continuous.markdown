---
layout: publication
title: 'Continuous Training And Fine-tuning For Domain-specific Language Models In Medical Question Answering'
authors: Zhen Guo, Yining Hua
conference: "Arxiv"
year: 2023
bibkey: guo2023continuous
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.00204'}
tags: ['Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Model Architecture', 'GPT', 'Pretraining Methods']
---
Large language models exhibit promising general capabilities but often lack
specialized knowledge for domain-specific tasks. Developing domain experts from
a base model enables a range of applications without prohibitive training
costs. This work demonstrates a method using continuous training and
instruction fine-tuning to rapidly adapt Llama 2 base models to the Chinese
medical domain. We first conduct continuous training on 1B tokens from Chinese
medical references to teach relevant vocabulary and knowledge. The models are
then fine-tuned on 54K examples sourced from the Chinese National Medical
Licensing Examination. Experiments on Chinese medical data confirm the
effectiveness of this approach, producing a model comparable to GPT-3.5-turbo
while using way less computational resource. The resulting domain-specific
model could be useful for various Chinese medical applications. More broadly,
this provides a template for domain-specific training of large language models
in areas where pre-trained models lack the required expertise, such as law,
science, and engineering.
