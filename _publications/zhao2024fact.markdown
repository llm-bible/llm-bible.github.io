---
layout: publication
title: 'Fact-and-reflection (far) Improves Confidence Calibration Of Large Language Models'
authors: Xinran Zhao, Hongming Zhang, Xiaoman Pan, Wenlin Yao, Dong Yu, Tongshuang Wu, Jianshu Chen
conference: "Findings of the Association for Computational Linguistics ACL 2024"
year: 2024
bibkey: zhao2024fact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17124"}
tags: ['Prompting']
---
For a LLM to be trustworthy, its confidence level should be well-calibrated
with its actual performance. While it is now common sense that LLM performances
are greatly impacted by prompts, the confidence calibration in prompting LLMs
has yet to be thoroughly explored. In this paper, we explore how different
prompting strategies influence LLM confidence calibration and how it could be
improved. We conduct extensive experiments on six prompting methods in the
question-answering context and we observe that, while these methods help
improve the expected LLM calibration, they also trigger LLMs to be
over-confident when responding to some instances. Inspired by human cognition,
we propose Fact-and-Reflection (FaR) prompting, which improves the LLM
calibration in two steps. First, FaR elicits the known "facts" that are
relevant to the input prompt from the LLM. And then it asks the model to
"reflect" over them to generate the final answer. Experiments show that FaR
prompting achieves significantly better calibration; it lowers the Expected
Calibration Error by 23.5% on our multi-purpose QA tasks. Notably, FaR
prompting even elicits the capability of verbally expressing concerns in less
confident scenarios, which helps trigger retrieval augmentation for solving
these harder instances.
