---
layout: publication
title: 'Rewarding Doubt: A Reinforcement Learning Approach To Calibrated Confidence Expression Of Large Language Models'
authors: Paul Stangel, David Bani-harouni, Chantal Pellegrini, Ege Özsoy, Kamilia Zaripova, Matthias Keicher, Nassir Navab
conference: "Arxiv"
year: 2025
bibkey: stangel2025rewarding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02623"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
A safe and trustworthy use of Large Language Models (LLMs) requires an accurate expression of confidence in their answers. We propose a novel Reinforcement Learning approach that allows to directly fine-tune LLMs to express calibrated confidence estimates alongside their answers to factual questions. Our method optimizes a reward based on the logarithmic scoring rule, explicitly penalizing both over- and under-confidence. This encourages the model to align its confidence estimates with the actual predictive accuracy. The optimal policy under our reward design would result in perfectly calibrated confidence expressions. Unlike prior approaches that decouple confidence estimation from response generation, our method integrates confidence calibration seamlessly into the generative process of the LLM. Empirically, we demonstrate that models trained with our approach exhibit substantially improved calibration and generalize to unseen tasks without further fine-tuning, suggesting the emergence of general confidence awareness. We provide our training and evaluation code in the supplementary and will make it publicly available upon acceptance.
