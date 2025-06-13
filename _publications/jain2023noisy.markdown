---
layout: publication
title: 'Neftune: Noisy Embeddings Improve Instruction Finetuning'
authors: Neel Jain, Ping-yeh Chiang, Yuxin Wen, John Kirchenbauer, Hong-min Chu, Gowthami Somepalli, Brian R. Bartoldson, Bhavya Kailkhura, Avi Schwarzschild, Aniruddha Saha, Micah Goldblum, Jonas Geiping, Tom Goldstein
conference: "Arxiv"
year: 2023
bibkey: jain2023noisy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05914"}
tags: ['Training Techniques', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
We show that language model finetuning can be improved, sometimes
dramatically, with a simple augmentation. NEFTune adds noise to the embedding
vectors during training. Standard finetuning of LLaMA-2-7B using Alpaca
achieves 29.79% on AlpacaEval, which rises to 64.69% using noisy embeddings.
NEFTune also improves over strong baselines on modern instruction datasets.
Models trained with Evol-Instruct see a 10% improvement, with ShareGPT an 8%
improvement, and with OpenPlatypus an 8% improvement. Even powerful models
further refined with RLHF such as LLaMA-2-Chat benefit from additional training
with NEFTune.
