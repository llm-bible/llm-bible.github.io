---
layout: publication
title: 'Prompt-based Bias Calibration For Better Zero/few-shot Learning Of Language Models'
authors: He Kang, Long Yinghan, Roy Kaushik
conference: "Arxiv"
year: 2024
bibkey: he2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10353"}
tags: ['Bias Mitigation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fairness', 'Few Shot', 'Fine Tuning', 'GPT', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Prompt learning is susceptible to intrinsic bias present in pre-trained
language models (LMs), resulting in sub-optimal performance of prompt-based
zero/few-shot learning. In this work, we propose a null-input prompting method
to calibrate intrinsic bias encoded in pre-trained LMs. Different from prior
efforts that address intrinsic bias primarily for social fairness and often
involve excessive computational cost, our objective is to explore enhancing
LMs' performance in downstream zero/few-shot learning while emphasizing the
efficiency of intrinsic bias calibration. Specifically, we leverage a diverse
set of auto-selected null-meaning inputs generated from GPT-4 to prompt
pre-trained LMs for intrinsic bias probing. Utilizing the bias-reflected
probability distribution, we formulate a distribution disparity loss for bias
calibration, where we exclusively update bias parameters (\\(0.1%\\) of total
parameters) of LMs towards equal probability distribution. Experimental results
show that the calibration promotes an equitable starting point for LMs while
preserving language modeling abilities. Across a wide range of datasets,
including sentiment analysis and topic classification, our method significantly
improves zero/few-shot learning performance of LMs for both in-context learning
and prompt-based fine-tuning (on average \\(9%\\) and \\(2%\\), respectively).
