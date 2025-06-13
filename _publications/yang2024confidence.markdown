---
layout: publication
title: 'Confidence V.s. Critique: A Decomposition Of Self-correction Capability For Llms'
authors: Zhe Yang, Yichang Zhang, Yudong Wang, Ziyao Xu, Junyang Lin, Zhifang Sui
conference: "Arxiv"
year: 2024
bibkey: yang2024confidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.19513"}
tags: ['Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) can correct their self-generated responses, but
a decline in accuracy after self-correction is also witnessed. To have a deeper
understanding of self-correction, we endeavor to decompose, evaluate, and
analyze the self-correction behaviors of LLMs. By enumerating and analyzing
answer correctness before and after self-correction, we decompose the
self-correction capability into confidence (being confident to correct answers)
and critique (turning wrong answers to correct) capabilities, and propose two
metrics from a probabilistic perspective to measure these 2 capabilities, along
with another metric for overall self-correction capability evaluation. Based on
our decomposition and evaluation metrics, we conduct extensive experiments and
draw some empirical conclusions. For example, we find different models can
exhibit distinct behaviors: some models are confident while others are more
critical. We also find the trade-off between the two capabilities (i.e.
improving one can lead to a decline in the other) when manipulating model
self-correction behavior by prompts or in-context learning. Further, we find a
simple yet efficient strategy to improve self-correction capability by
transforming Supervision Fine-Tuning (SFT) data format, and our strategy
outperforms vanilla SFT in both capabilities and achieves much higher accuracy
after self-correction. Our code will be publicly available on GitHub.
