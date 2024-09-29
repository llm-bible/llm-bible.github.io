---
layout: publication
title: "Stochastic Parrots Looking For Stochastic Parrots: Llms Are Easy To Fine-tune And Hard To Detect With Other Llms"
authors: Henrique Da Silva Gameiro, Kucharavy Andrei, Guerraoui Rachid
conference: "Arxiv"
year: 2023
bibkey: henrique2023stochastic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.08968"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques', 'Transformer']
---
The self-attention revolution allowed generative language models to scale and achieve increasingly impressive abilities. Such models - commonly referred to as Large Language Models (LLMs) - have recently gained prominence with the general public thanks to conversational fine-tuning putting their behavior in line with public expectations regarding AI. This prominence amplified prior concerns regarding the misuse of LLMs and led to the emergence of numerous tools to detect LLMs in the wild. Unfortunately most such tools are critically flawed. While major publications in the LLM detectability field suggested that LLMs were easy to detect with fine-tuned autoencoders the limitations of their results are easy to overlook. Specifically they assumed publicly available generative models without fine-tunes or non-trivial prompts. While the importance of these assumptions has been demonstrated until now it remained unclear how well such detection could be countered. Here we show that an attacker with access to such detectors reference human texts and output not only evades detection but can fully frustrate the detector training - with a reasonable budget and all its outputs labeled as such. Achieving it required combining common reinforcement from critic loss function modification and AdamW optimizer which led to surprisingly good fine-tuning generalization. Finally we warn against the temptation to transpose the conclusions obtained in RNN-driven text GANs to LLMs due to their better representative ability. These results have critical implications for the detection and prevention of malicious use of generative language models and we hope they will aid the designers of generative models and detectors.
