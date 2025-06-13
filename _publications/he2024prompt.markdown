---
layout: publication
title: 'Prompt-based Bias Calibration For Better Zero/few-shot Learning Of Language Models'
authors: Kang He, Yinghan Long, Kaushik Roy
conference: "Arxiv"
year: 2024
bibkey: he2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10353"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fairness', 'Few-Shot', 'Model Architecture', 'RAG', 'Language Modeling', 'GPT', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Prompt-based learning is susceptible to intrinsic bias present in pre-trained
language models (LMs), leading to sub-optimal performance in prompt-based
zero/few-shot settings. In this work, we propose a null-input prompting method
to calibrate intrinsic bias encoded in pre-trained LMs. Different from prior
efforts that address intrinsic bias primarily for social fairness and often
involve excessive computational cost, our objective is to explore enhancing
LMs' performance in downstream zero/few-shot learning while emphasizing the
efficiency of intrinsic bias calibration. Specifically, we leverage a diverse
set of auto-selected null-meaning inputs generated from GPT-4 to probe
intrinsic bias of pre-trained LMs. Utilizing the bias-reflected probability
distribution, we formulate a distribution disparity loss for bias calibration,
where we exclusively update bias parameters (\\(0.1%\\) of total parameters) of
LMs towards equal probability distribution. Experimental results show that the
calibration promotes an equitable starting point for LMs while preserving
language modeling abilities. Across a wide range of datasets, including
sentiment analysis and topic classification, our method significantly improves
zero/few-shot learning performance of LMs for both in-context learning and
prompt-based fine-tuning (on average \\(9%\\) and \\(2%\\), respectively).
