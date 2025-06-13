---
layout: publication
title: 'On The Calibration Of Multilingual Question Answering Llms'
authors: Yahan Yang, Soham Dan, Dan Roth, Insup Lee
conference: "Arxiv"
year: 2023
bibkey: yang2023calibration
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.08669'}
tags: ['Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Multilingual pre-trained Large Language Models (LLMs) are incredibly
effective at Question Answering (QA), a core task in Natural Language
Understanding, achieving high accuracies on several multilingual benchmarks.
However, little is known about how well their confidences are calibrated. In
this paper, we comprehensively benchmark the calibration of several
multilingual LLMs (MLLMs) on a variety of QA tasks. We perform extensive
experiments, spanning encoder-only, encoder-decoder, and decoder-only QA models
(size varying from 110M to 7B parameters) and diverse languages, including both
high- and low-resource ones. We study different dimensions of calibration in
in-distribution, out-of-distribution, and cross-lingual transfer settings, and
investigate strategies to improve it, including post-hoc methods and
regularized fine-tuning. For decoder-only LLMs such as LlaMa2, we additionally
find that in-context learning improves confidence calibration on multilingual
data. We also conduct several ablation experiments to study the effect of
language distances, language corpus size, and model size on calibration, and
how multilingual models compare with their monolingual counterparts for diverse
tasks and languages. Our experiments suggest that the multilingual QA models
are poorly calibrated for languages other than English and incorporating a
small set of cheaply translated multilingual samples during
fine-tuning/calibration effectively enhances the calibration performance.
