---
layout: publication
title: 'Emafusion: A Self-optimizing System For Seamless LLM Selection And Integration'
authors: Soham Shah, Kumar Shridhar, Surojit Chatterjee, Souvik Sen
conference: "Arxiv"
year: 2025
bibkey: shah2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.10681'}
tags: ['RAG', 'Security', 'Model Architecture', 'GPT', 'Tools', 'Merging', 'Reinforcement Learning', 'Ethics and Bias']
---
While recent advances in large language models (LLMs) have significantly
enhanced performance across diverse natural language tasks, the high
computational and financial costs associated with their deployment remain
substantial barriers. Existing routing strategies partially alleviate this
challenge by assigning queries to cheaper or specialized models, but they
frequently rely on extensive labeled data or fragile task-specific heuristics.
Conversely, fusion techniques aggregate multiple LLM outputs to boost accuracy
and robustness, yet they often exacerbate cost and may reinforce shared biases.
  We introduce EMAFusion, a new framework that self-optimizes for seamless LLM
selection and reliable execution for a given query. Specifically, EMAFusion
integrates a taxonomy-based router for familiar query types, a learned router
for ambiguous inputs, and a cascading approach that progressively escalates
from cheaper to more expensive models based on multi-judge confidence
evaluations. Through extensive evaluations, we find EMAFusion outperforms the
best individual models by over 2.6 percentage points (94.3% vs. 91.7%), while
being 4X cheaper than the average cost. EMAFusion further achieves a remarkable
17.1 percentage point improvement over models like GPT-4 at less than 1/20th
the cost. Our combined routing approach delivers 94.3% accuracy compared to
taxonomy-based (88.1%) and learned model predictor-based (91.7%) methods alone,
demonstrating the effectiveness of our unified strategy. Finally, EMAFusion
supports flexible cost-accuracy trade-offs, allowing users to balance their
budgetary constraints and performance needs.
