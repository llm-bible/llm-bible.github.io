---
layout: publication
title: 'Winning Amazon KDD Cup''24'
authors: Chris Deotte, Ivan Sorokin, Ahmet Erdem, Benedikt Schifferer, Gilberto Jr Titericz, Simon Jegou
conference: "Arxiv"
year: 2024
bibkey: deotte2024winning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.04658'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Fine-Tuning', 'KDD']
---
This paper describes the winning solution of all 5 tasks for the Amazon KDD
Cup 2024 Multi Task Online Shopping Challenge for LLMs. The challenge was to
build a useful assistant, answering questions in the domain of online shopping.
The competition contained 57 diverse tasks, covering 5 different task types
(e.g. multiple choice) and across 4 different tracks (e.g. multi-lingual). Our
solution is a single model per track. We fine-tune Qwen2-72B-Instruct on our
own training dataset. As the competition released only 96 example questions, we
developed our own training dataset by processing multiple public datasets or
using Large Language Models for data augmentation and synthetic data
generation. We apply wise-ft to account for distribution shifts and ensemble
multiple LoRA adapters in one model. We employed Logits Processors to constrain
the model output on relevant tokens for the tasks. AWQ 4-bit Quantization and
vLLM are used during inference to predict the test dataset in the time
constraints of 20 to 140 minutes depending on the track. Our solution achieved
the first place in each individual track and is the first place overall of
Amazons KDD Cup 2024.
