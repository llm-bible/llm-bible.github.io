---
layout: publication
title: 'Probabilities Of Chat Llms Are Miscalibrated But Still Predict Correctness On Multiple-choice Q&A'
authors: Benjamin Plaut, Nguyen X. Khanh, Tu Trinh
conference: "Arxiv"
year: 2024
bibkey: plaut2024probabilities
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13213"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
We study 15 large language models (LLMs) fine-tuned for chat and find that
their maximum softmax probabilities (MSPs) are consistently miscalibrated on
multiple-choice Q&A. However, those MSPs might still encode useful uncertainty
information. Specifically, we hypothesized that wrong answers would be
associated with smaller MSPs compared to correct answers. Via rigorous
statistical testing, we show that this hypothesis holds for models which
perform well on the underlying Q&A task. We also find a strong direction
correlation between Q&A accuracy and MSP correctness prediction, while finding
no correlation between Q&A accuracy and calibration error. This suggests that
within the current fine-tuning paradigm, we can expect correctness prediction
but not calibration to improve as LLM capabilities progress. To demonstrate the
utility of correctness prediction, we show that when models have the option to
abstain, performance can be improved by selectively abstaining based on the MSP
of the initial model response, using only a small amount of labeled data to
choose the MSP threshold.
