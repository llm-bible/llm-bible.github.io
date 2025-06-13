---
layout: publication
title: 'Detecting LLM Fact-conflicting Hallucinations Enhanced By Temporal-logic-based Reasoning'
authors: Ningke Li, Yahui Song, Kailong Wang, Yuekang Li, Ling Shi, Yi Liu, Haoyu Wang
conference: "Arxiv"
year: 2025
bibkey: li2025detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13416"}
tags: ['Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'ACL', 'Prompting']
---
Large language models (LLMs) face the challenge of hallucinations -- outputs
that seem coherent but are actually incorrect. A particularly damaging type is
fact-conflicting hallucination (FCH), where generated content contradicts
established facts. Addressing FCH presents three main challenges: 1)
Automatically constructing and maintaining large-scale benchmark datasets is
difficult and resource-intensive; 2) Generating complex and efficient test
cases that the LLM has not been trained on -- especially those involving
intricate temporal features -- is challenging, yet crucial for eliciting
hallucinations; and 3) Validating the reasoning behind LLM outputs is
inherently difficult, particularly with complex logical relationships, as it
requires transparency in the model's decision-making process.
  This paper presents Drowzee, an innovative end-to-end metamorphic testing
framework that utilizes temporal logic to identify fact-conflicting
hallucinations (FCH) in large language models (LLMs). Drowzee builds a
comprehensive factual knowledge base by crawling sources like Wikipedia and
uses automated temporal-logic reasoning to convert this knowledge into a large,
extensible set of test cases with ground truth answers. LLMs are tested using
these cases through template-based prompts, which require them to generate both
answers and reasoning steps. To validate the reasoning, we propose two
semantic-aware oracles that compare the semantic structure of LLM outputs to
the ground truths. Across nine LLMs in nine different knowledge domains,
experimental results show that Drowzee effectively identifies rates of
non-temporal-related hallucinations ranging from 24.7% to 59.8%, and rates of
temporal-related hallucinations ranging from 16.7% to 39.2%.
