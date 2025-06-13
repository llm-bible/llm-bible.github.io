---
layout: publication
title: 'Harnessing Large Language Models For Text-rich Sequential Recommendation'
authors: Zhi Zheng, Wenshuo Chao, Zhaopeng Qiu, Hengshu Zhu, Hui Xiong
conference: "Arxiv"
year: 2024
bibkey: zheng2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13325"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RecSys', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Recent advances in Large Language Models (LLMs) have been changing the
paradigm of Recommender Systems (RS). However, when items in the recommendation
scenarios contain rich textual information, such as product descriptions in
online shopping or news headlines on social media, LLMs require longer texts to
comprehensively depict the historical user behavior sequence. This poses
significant challenges to LLM-based recommenders, such as over-length
limitations, extensive time and space overheads, and suboptimal model
performance. To this end, in this paper, we design a novel framework for
harnessing Large Language Models for Text-Rich Sequential Recommendation
(LLM-TRSR). Specifically, we first propose to segment the user historical
behaviors and subsequently employ an LLM-based summarizer for summarizing these
user behavior blocks. Particularly, drawing inspiration from the successful
application of Convolutional Neural Networks (CNN) and Recurrent Neural
Networks (RNN) models in user modeling, we introduce two unique summarization
techniques in this paper, respectively hierarchical summarization and recurrent
summarization. Then, we construct a prompt text encompassing the user
preference summary, recent user interactions, and candidate item information
into an LLM-based recommender, which is subsequently fine-tuned using
Supervised Fine-Tuning (SFT) techniques to yield our final recommendation
model. We also use Low-Rank Adaptation (LoRA) for Parameter-Efficient
Fine-Tuning (PEFT). We conduct experiments on two public datasets, and the
results clearly demonstrate the effectiveness of our approach.
