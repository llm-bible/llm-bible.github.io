---
layout: publication
title: Dynamo Accelerating Language Model Inference With Dynamic Multi45;token Sampling
authors: Tuli Shikhar, Lin Chi-heng, Hsu Yen-chang, Jha Niraj K., Shen Yilin, Jin Hongxia
conference: "Arxiv"
year: 2024
bibkey: tuli2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00888"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Traditional language models operate autoregressively i.e. they predict one token at a time. Rapid explosion in model sizes has resulted in high inference times. In this work we propose DynaMo a suite of multi45;token prediction language models that reduce net inference times. Our models textit123;dynamically125; predict multiple tokens based on their confidence in the predicted joint probability distribution. We propose a lightweight technique to train these models leveraging the weights of traditional autoregressive counterparts. Moreover we propose novel ways to enhance the estimated joint probability to improve text generation quality namely co45;occurrence weighted masking and adaptive thresholding. We also propose systematic qualitative and quantitative methods to rigorously test the quality of generated text for non45;autoregressive generation. One of the models in our suite DynaMo45;7.3B45;T3 achieves same45;quality generated text as the baseline (Pythia45;6.9B) while achieving 2.57× speed45;up with only 5.8737; and 2.6737; parameter and training time overheads respectively.
