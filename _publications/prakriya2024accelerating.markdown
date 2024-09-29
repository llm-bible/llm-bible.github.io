---
layout: publication
title: "Accelerating Large Language Model Pretraining Via LFR Pedagogy: Learn, Focus, And Review"
authors: Prakriya Neha, Yen Jui-nan, Hsieh Cho-jui, Cong Jason
conference: "Arxiv"
year: 2024
bibkey: prakriya2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06131"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Survey Paper', 'Training Techniques']
---
Large Language Model (LLM) pretraining traditionally relies on autoregressive language modeling on randomly sampled data blocks from web-scale datasets. We take inspiration from human learning techniques like spaced repetition to hypothesize that random data sampling for LLMs leads to high training cost and low quality models which tend to forget data. In order to effectively commit web-scale information to long-term memory we propose the LFR (Learn Focus and Review) pedagogy a new dynamic training paradigm which focuses and repeatedly reviews complex data blocks at systematic intervals based on the models learning pace and progress. LFR records the model perplexities for different data blocks and frequently revisits blocks with higher perplexity which are more likely to be forgotten. We pretrain the GPT-2 models (124M - 1.5B) from scratch on the OpenWebText dataset using LFR. We test on downstream tasks from the language modeling question answering translation and problem solving domains to achieve consistently lower perplexity and higher accuracy than the baseline OpenAI models while obtaining a 20x pretraining speed-up.
