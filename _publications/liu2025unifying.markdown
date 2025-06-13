---
layout: publication
title: 'UFT: Unifying Supervised And Reinforcement Fine-tuning'
authors: Mingyang Liu, Gabriele Farina, Asuman Ozdaglar
conference: "Arxiv"
year: 2025
bibkey: liu2025unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16984"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods', 'Reinforcement Learning']
---
Post-training has demonstrated its importance in enhancing the reasoning capabilities of large language models (LLMs). The primary post-training methods can be categorized into supervised fine-tuning (SFT) and reinforcement fine-tuning (RFT). SFT is efficient and well-suited for small language models, but it may lead to overfitting and limit the reasoning abilities of larger models. In contrast, RFT generally yields better generalization but depends heavily on the strength of the base model. To address the limitations of SFT and RFT, we propose Unified Fine-Tuning (UFT), a novel post-training paradigm that unifies SFT and RFT into a single, integrated process. UFT enables the model to effectively explore solutions while incorporating informative supervision signals, bridging the gap between memorizing and thinking underlying existing methods. Notably, UFT outperforms both SFT and RFT in general, regardless of model sizes. Furthermore, we theoretically prove that UFT breaks RFT's inherent exponential sample complexity bottleneck, showing for the first time that unified training can exponentially accelerate convergence on long-horizon reasoning tasks.
