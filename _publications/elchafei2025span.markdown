---
layout: publication
title: 'Span-level Hallucination Detection For Llm-generated Answers'
authors: Passant Elchafei, Mervet Abu-elkheir
conference: "Arxiv"
year: 2025
bibkey: elchafei2025span
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18639"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'BERT', 'Prompting']
---
Detecting spans of hallucination in LLM-generated answers is crucial for
improving factual consistency. This paper presents a span-level hallucination
detection framework for the SemEval-2025 Shared Task, focusing on English and
Arabic texts. Our approach integrates Semantic Role Labeling (SRL) to decompose
the answer into atomic roles, which are then compared with a retrieved
reference context obtained via question-based LLM prompting. Using a
DeBERTa-based textual entailment model, we evaluate each role semantic
alignment with the retrieved context. The entailment scores are further refined
through token-level confidence measures derived from output logits, and the
combined scores are used to detect hallucinated spans. Experiments on the
Mu-SHROOM dataset demonstrate competitive performance. Additionally,
hallucinated spans have been verified through fact-checking by prompting GPT-4
and LLaMA. Our findings contribute to improving hallucination detection in
LLM-generated responses.
