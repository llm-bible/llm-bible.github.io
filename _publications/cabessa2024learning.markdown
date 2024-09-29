---
layout: publication
title: In-Context Learning and Fine-Tuning GPT for Argument Mining
authors: Cabessa Jérémie, Hernault Hugo, Mushtaq Umer
conference: "Arxiv"
year: 2024
bibkey: cabessa2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06699"}
tags: ['Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have become ubiquitous in NLP and deep learning. In-Context Learning (ICL) has been suggested as a bridging paradigm between the training-free and fine-tuning LLMs settings. In ICL an LLM is conditioned to solve tasks by means of a few solved demonstration examples included as prompt. Argument Mining (AM) aims to extract the complex argumentative structure of a text and Argument Type Classification (ATC) is an essential sub-task of AM. We introduce an ICL strategy for ATC combining kNN-based examples selection and majority vote ensembling. In the training-free ICL setting we show that GPT-4 is able to leverage relevant information from only a few demonstration examples and achieve very competitive classification accuracy on ATC. We further set up a fine-tuning strategy incorporating well-crafted structural features given directly in textual form. In this setting GPT-3.5 achieves state-of-the-art performance on ATC. Overall these results emphasize the emergent ability of LLMs to grasp global discursive flow in raw text in both off-the-shelf and fine-tuned setups.
