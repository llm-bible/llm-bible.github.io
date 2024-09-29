---
layout: publication
title: Fact-and-Reflection (FaR) Improves Confidence Calibration of Large Language Models
authors: Zhao Xinran, Zhang Hongming, Pan Xiaoman, Yao Wenlin, Yu Dong, Wu Tongshuang, Chen Jianshu
conference: "Findings of the Association for Computational Linguistics ACL"
year: 2024
bibkey: zhao2024fact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17124"}
tags: ['Applications', 'Prompting']
---
For a LLM to be trustworthy its confidence level should be well-calibrated with its actual performance. While it is now common sense that LLM performances are greatly impacted by prompts the confidence calibration in prompting LLMs has yet to be thoroughly explored. In this paper we explore how different prompting strategies influence LLM confidence calibration and how it could be improved. We conduct extensive experiments on six prompting methods in the question-answering context and we observe that while these methods help improve the expected LLM calibration they also trigger LLMs to be over-confident when responding to some instances. Inspired by human cognition we propose Fact-and-Reflection (FaR) prompting which improves the LLM calibration in two steps. First FaR elicits the known facts that are relevant to the input prompt from the LLM. And then it asks the model to reflect over them to generate the final answer. Experiments show that FaR prompting achieves significantly better calibration; it lowers the Expected Calibration Error by 23.5 on our multi-purpose QA tasks. Notably FaR prompting even elicits the capability of verbally expressing concerns in less confident scenarios which helps trigger retrieval augmentation for solving these harder instances.
