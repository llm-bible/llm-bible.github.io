---
layout: publication
title: 'Diverseagententropy: Quantifying Black-box LLM Uncertainty Through Diverse Perspectives And Multi-agent Interaction'
authors: Yu Feng, Phu Mon Htut, Zheng Qi, Wei Xiao, Manuel Mager, Nikolaos Pappas, Kishaloy Halder, Yang Li, Yassine Benajiba, Dan Roth
conference: "Arxiv"
year: 2024
bibkey: feng2024quantifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.09572'}
tags: ['Agentic']
---
Quantifying the uncertainty in the factual parametric knowledge of Large
Language Models (LLMs), especially in a black-box setting, poses a significant
challenge. Existing methods, which gauge a model's uncertainty through
evaluating self-consistency in responses to the original query, do not always
capture true uncertainty. Models might respond consistently to the origin query
with a wrong answer, yet respond correctly to varied questions from different
perspectives about the same query, and vice versa. In this paper, we propose a
novel method, DiverseAgentEntropy, for evaluating a model's uncertainty using
multi-agent interaction under the assumption that if a model is certain, it
should consistently recall the answer to the original query across a diverse
collection of questions about the same original query. We further implement an
abstention policy to withhold responses when uncertainty is high. Our method
offers a more accurate prediction of the model's reliability and further
detects hallucinations, outperforming other self-consistency-based methods.
Additionally, it demonstrates that existing models often fail to consistently
retrieve the correct answer to the same query under diverse varied questions
even when knowing the correct answer.
