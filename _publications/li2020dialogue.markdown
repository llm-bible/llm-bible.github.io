---
layout: publication
title: 'Dialogue-adaptive Language Model Pre-training From Quality Estimation'
authors: Li Junlong, Zhang Zhuosheng, Zhao Hai
conference: "Arxiv"
year: 2020
bibkey: li2020dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.04984"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
"Pre-trained language models (PrLMs) have achieved great success on a wide range of natural language processing tasks by virtue of the universal language representation ability obtained by self-supervised learning on a large corpus. These models are pre-trained on standard plain texts with general language model (LM) training objectives, which would be insufficient to model dialogue-exclusive attributes like specificity and informativeness reflected in these tasks that are not explicitly captured by the pre-trained universal language representations. In this work, we propose dialogue-adaptive pre-training objectives (DAPO) derived from quality estimation to simulate dialogue-specific features, namely coherence, specificity, and informativeness. As the foundation for model pre-training, we synthesize a new dialogue corpus and build our training set with two unsupervised methods: 1) coherence-oriented context corruption, including utterance ordering, insertion, and replacement, to help the model capture the coherence inside the dialogue contexts; and 2) specificity-oriented automatic rescoring, which encourages the model to measure the quality of the synthesized data for dialogue-adaptive pre-training by considering specificity and informativeness. Experimental results on widely used open-domain response selection and quality estimation benchmarks show that DAPO significantly improves the baseline models and achieves state-of-the-art performance on the MuTual leaderboard, verifying the effectiveness of estimating quality evaluation factors into pre-training."
