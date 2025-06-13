---
layout: publication
title: 'DEBATE: Devil''s Advocate-based Assessment And Text Evaluation'
authors: Alex Kim, Keonwoo Kim, Sangwon Yoon
conference: "Arxiv"
year: 2024
bibkey: kim2024advocate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.09935"}
tags: ['Agentic', 'Ethics and Bias', 'Tools']
---
As natural language generation (NLG) models have become prevalent,
systematically assessing the quality of machine-generated texts has become
increasingly important. Recent studies introduce LLM-based evaluators that
operate as reference-free metrics, demonstrating their capability to adeptly
handle novel tasks. However, these models generally rely on a single-agent
approach, which, we argue, introduces an inherent limit to their performance.
This is because there exist biases in LLM agent's responses, including
preferences for certain text structure or content. In this work, we propose
DEBATE, an NLG evaluation framework based on multi-agent scoring system
augmented with a concept of Devil's Advocate. Within the framework, one agent
is instructed to criticize other agents' arguments, potentially resolving the
bias in LLM agent's answers. DEBATE substantially outperforms the previous
state-of-the-art methods in two meta-evaluation benchmarks in NLG evaluation,
SummEval and TopicalChat. We also show that the extensiveness of debates among
agents and the persona of an agent can influence the performance of evaluators.
