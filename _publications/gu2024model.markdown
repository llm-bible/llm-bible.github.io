---
layout: publication
title: Model Editing Harms General Abilities of Large Language Models Regularization to the Rescue
authors: Gu Jia-chen, Xu Hao-xiang, Ma Jun-yu, Lu Pan, Ling Zhen-hua, Chang Kai-wei, Peng Nanyun
conference: "Arxiv"
year: 2024
bibkey: gu2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.04700"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Model editing is a technique that edits the large language models (LLMs) with updated knowledge to alleviate hallucinations without resource-intensive retraining. While current model editing methods can effectively modify a models behavior within a specific area of interest they often overlook the potential unintended side effects on the general abilities of LLMs such as reasoning natural language inference and question answering. In this paper we raise concerns that model editings improvements on factuality may come at the cost of a significant degradation of the models general abilities. We systematically analyze the side effects by evaluating four popular editing methods on three LLMs across eight representative tasks. Our extensive empirical experiments show that it is challenging for current editing methods to simultaneously improve factuality of LLMs and maintain their general abilities. Our analysis reveals that the side effects are caused by model editing altering the original model weights excessively leading to overfitting to the edited facts. To mitigate this a method named RECT (RElative Change in weighT) is proposed to regularize the edit update weights. Evaluation results show that RECT can significantly mitigate the side effects of editing while still maintaining over 94 editing performance.
