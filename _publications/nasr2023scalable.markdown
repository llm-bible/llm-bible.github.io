---
layout: publication
title: Scalable Extraction Of Training Data From (production) Language Models
authors: Nasr Milad, Carlini Nicholas, Hayase Jonathan, Jagielski Matthew, Cooper A. Feder, Ippolito Daphne, Choquette-choo Christopher A., Wallace Eric, Tramèr Florian, Lee Katherine
conference: "Arxiv"
year: 2023
bibkey: nasr2023scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17035"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
This paper studies extractable memorization training data that an adversary can efficiently extract by querying a machine learning model without prior knowledge of the training dataset. We show an adversary can extract gigabytes of training data from open-source language models like Pythia or GPT-Neo semi-open models like LLaMA or Falcon and closed models like ChatGPT. Existing techniques from the literature suffice to attack unaligned models; in order to attack the aligned ChatGPT we develop a new divergence attack that causes the model to diverge from its chatbot-style generations and emit training data at a rate 150x higher than when behaving properly. Our methods show practical attacks can recover far more data than previously thought and reveal that current alignment techniques do not eliminate memorization.
