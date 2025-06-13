---
layout: publication
title: 'Uncertainty-aware Evaluation For Vision-language Models'
authors: Vasily Kostumov, Bulat Nutfullin, Oleg Pilipenko, Eugene Ilyushin
conference: "Arxiv"
year: 2024
bibkey: kostumov2024uncertainty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14418"}
tags: ['GPT', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning']
---
Vision-Language Models like GPT-4, LLaVA, and CogVLM have surged in
popularity recently due to their impressive performance in several
vision-language tasks. Current evaluation methods, however, overlook an
essential component: uncertainty, which is crucial for a comprehensive
assessment of VLMs. Addressing this oversight, we present a benchmark
incorporating uncertainty quantification into evaluating VLMs.
  Our analysis spans 20+ VLMs, focusing on the multiple-choice Visual Question
Answering (VQA) task. We examine models on 5 datasets that evaluate various
vision-language capabilities.
  Using conformal prediction as an uncertainty estimation approach, we
demonstrate that the models' uncertainty is not aligned with their accuracy.
Specifically, we show that models with the highest accuracy may also have the
highest uncertainty, which confirms the importance of measuring it for VLMs.
Our empirical findings also reveal a correlation between model uncertainty and
its language model part.
