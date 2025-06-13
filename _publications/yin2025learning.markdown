---
layout: publication
title: 'Learning Composable Chains-of-thought'
authors: Fangcong Yin, Zeyu Leo Liu, Liu Leqi, Xi Ye, Greg Durrett
conference: "Arxiv"
year: 2025
bibkey: yin2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22635"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Merging']
---
A common approach for teaching large language models (LLMs) to reason is to train on chain-of-thought (CoT) traces of in-distribution reasoning problems, but such annotated data is costly to obtain for every problem of interest. We want reasoning models to generalize beyond their training distribution, and ideally to generalize compositionally: combine atomic reasoning skills to solve harder, unseen reasoning tasks. We take a step towards compositional generalization of reasoning skills when addressing a target compositional task that has no labeled CoT data. We find that simply training models on CoT data of atomic tasks leads to limited generalization, but minimally modifying CoT formats of constituent atomic tasks to be composable can lead to improvements. We can train "atomic CoT" models on the atomic tasks with Composable CoT data and combine them with multitask learning or model merging for better zero-shot performance on the target compositional task. Such a combined model can be further bootstrapped on a small amount of compositional data using rejection sampling fine-tuning (RFT). Results on string operations and natural language skill compositions show that training LLMs on Composable CoT outperforms multitask learning and continued fine-tuning baselines within a given training data budget.
