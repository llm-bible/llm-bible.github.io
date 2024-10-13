---
layout: publication
title: 'Multilingual Brain Surgeon: Large Language Models Can Be Compressed Leaving No Language Behind'
authors: Zeng Hongchuan, Xu Hongshen, Chen Lu, Yu Kai
conference: "Arxiv"
year: 2024
bibkey: zeng2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04748"}
tags: ['Efficiency And Optimization', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have ushered in a new era in Natural Language
Processing, but their massive size demands effective compression techniques for
practicality. Although numerous model compression techniques have been
investigated, they typically rely on a calibration set that overlooks the
multilingual context and results in significant accuracy degradation for
low-resource languages. This paper introduces Multilingual Brain Surgeon (MBS),
a novel calibration data sampling method for multilingual LLMs compression. MBS
overcomes the English-centric limitations of existing methods by sampling
calibration data from various languages proportionally to the language
distribution of the model training datasets. Our experiments, conducted on the
BLOOM multilingual LLM, demonstrate that MBS improves the performance of
existing English-centric compression methods, especially for low-resource
languages. We also uncover the dynamics of language interaction during
compression, revealing that the larger the proportion of a language in the
training set and the more similar the language is to the calibration language,
the better performance the language retains after compression. In conclusion,
MBS presents an innovative approach to compressing multilingual LLMs,
addressing the performance disparities and improving the language inclusivity
of existing compression techniques.
