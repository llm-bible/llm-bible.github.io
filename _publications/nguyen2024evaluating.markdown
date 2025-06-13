---
layout: publication
title: 'Semikong: Curating, Training, And Evaluating A Semiconductor Industry-specific Large Language Model'
authors: Christopher Nguyen, William Nguyen, Atsushi Suzuki, Daisuke Oku, Hong An Phan, Sang Dinh, Zooey Nguyen, Anh Ha, Shruti Raghavan, Huy Vo, Thang Nguyen, Lan Nguyen, Yoshikuni Hirayama
conference: "Arxiv"
year: 2024
bibkey: nguyen2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.13802'}
  - {name: "Code", url: 'https://github.com/aitomatic/semikong'}
tags: ['Has Code', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated the potential to address some
issues within the semiconductor industry. However, they are often
general-purpose models that lack the specialized knowledge needed to tackle the
unique challenges of this sector, such as the intricate physics and chemistry
of semiconductor devices and processes. SemiKong, the first industry-specific
LLM for the semiconductor domain, provides a foundation that can be used to
develop tailored proprietary models. With SemiKong 1.0, we aim to develop a
foundational model capable of understanding etching problems at an expert
level. Our key contributions include (a) curating a comprehensive corpus of
semiconductor-related texts, (b) creating a foundational model with in-depth
semiconductor knowledge, and (c) introducing a framework for integrating expert
knowledge, thereby advancing the evaluation process of domain-specific AI
models. Through fine-tuning a pre-trained LLM using our curated dataset, we
have shown that SemiKong outperforms larger, general-purpose LLMs in various
semiconductor manufacturing and design tasks. Our extensive experiments
underscore the importance of developing domain-specific LLMs as a foundation
for company- or tool-specific proprietary models, paving the way for further
research and applications in the semiconductor domain. Code and dataset will be
available at https://github.com/aitomatic/semikong
