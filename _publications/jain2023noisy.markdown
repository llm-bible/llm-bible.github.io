---
layout: publication
title: 'Neftune: Noisy Embeddings Improve Instruction Finetuning'
authors: Jain Neel, Chiang Ping-yeh, Wen Yuxin, Kirchenbauer John, Chu Hong-min, Somepalli Gowthami, Bartoldson Brian R., Kailkhura Bhavya, Schwarzschild Avi, Saha Aniruddha, Goldblum Micah, Geiping Jonas, Goldstein Tom
conference: "Arxiv"
year: 2023
bibkey: jain2023noisy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05914"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We show that language model finetuning can be improved sometimes dramatically with a simple augmentation. NEFTune adds noise to the embedding vectors during training. Standard finetuning of LLaMA-2-7B using Alpaca achieves 29.7937; on AlpacaEval which rises to 64.6937; using noisy embeddings. NEFTune also improves over strong baselines on modern instruction datasets. Models trained with Evol-Instruct see a 1037; improvement with ShareGPT an 837; improvement and with OpenPlatypus an 837; improvement. Even powerful models further refined with RLHF such as LLaMA-2-Chat benefit from additional training with NEFTune.
