---
layout: publication
title: 'Would I Lie To You? Inference Time Alignment Of Language Models Using Direct Preference Heads'
authors: Hadji-kyriacou Avelina Asada, Arandjelovic Ognjen
conference: "Arxiv"
year: 2024
bibkey: hadjikyriacou2024would
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20053"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Pre-trained Language Models (LMs) exhibit strong zero-shot and in-context
learning capabilities; however, their behaviors are often difficult to control.
By utilizing Reinforcement Learning from Human Feedback (RLHF), it is possible
to fine-tune unsupervised LMs to follow instructions and produce outputs that
reflect human preferences. Despite its benefits, RLHF has been shown to
potentially harm a language model's reasoning capabilities and introduce
artifacts such as hallucinations where the model may fabricate facts. To
address this issue we introduce Direct Preference Heads (DPH), a fine-tuning
framework that enables LMs to learn human preference signals through an
auxiliary reward head without directly affecting the output distribution of the
language modeling head. We perform a theoretical analysis of our objective
function and find strong ties to Conservative Direct Preference Optimization
(cDPO). Finally we evaluate our models on GLUE, RACE, and the GPT4All
evaluation suite and demonstrate that our method produces models which achieve
higher scores than those fine-tuned with Supervised Fine-Tuning (SFT) or Direct
Preference Optimization (DPO) alone.
