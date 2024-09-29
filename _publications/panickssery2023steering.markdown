---
layout: publication
title: Steering Llama 2 via Contrastive Activation Addition
authors: Panickssery Nina, Gabrieli Nick, Schulz Julian, Tong Meg, Hubinger Evan, Turner Alexander Matt
conference: "Arxiv"
year: 2023
bibkey: panickssery2023steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06681"}
tags: ['Prompting', 'RAG']
---
We introduce Contrastive Activation Addition (CAA) an innovative method for steering language models by modifying their activations during forward passes. CAA computes steering vectors by averaging the difference in residual stream activations between pairs of positive and negative examples of a particular behavior such as factual versus hallucinatory responses. During inference these steering vectors are added at all token positions after the users prompt with either a positive or negative coefficient allowing precise control over the degree of the targeted behavior. We evaluate CAAs effectiveness on Llama 2 Chat using multiple-choice behavioral question datasets and open-ended generation tasks. We demonstrate that CAA significantly alters model behavior is effective over and on top of traditional methods like finetuning and system prompt design and minimally reduces capabilities. Moreover we gain deeper insights into CAAs mechanisms by employing various activation space interpretation methods. CAA accurately steers model outputs and sheds light on how high-level concepts are represented in Large Language Models (LLMs).
