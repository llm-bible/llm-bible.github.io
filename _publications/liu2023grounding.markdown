---
layout: publication
title: 'Grounding Complex Natural Language Commands For Temporal Tasks In Unseen Environments'
authors: Jason Xinyu Liu, Ziyi Yang, Ifrah Idrees, Sam Liang, Benjamin Schornstein, Stefanie Tellex, Ankit Shah
conference: "Arxiv"
year: 2023
bibkey: liu2023grounding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2302.11649'}
tags: ['RAG', 'Training Techniques']
---
Grounding navigational commands to linear temporal logic (LTL) leverages its
unambiguous semantics for reasoning about long-horizon tasks and verifying the
satisfaction of temporal constraints. Existing approaches require training data
from the specific environment and landmarks that will be used in natural
language to understand commands in those environments. We propose Lang2LTL, a
modular system and a software package that leverages large language models
(LLMs) to ground temporal navigational commands to LTL specifications in
environments without prior language data. We comprehensively evaluate Lang2LTL
for five well-defined generalization behaviors. Lang2LTL demonstrates the
state-of-the-art ability of a single model to ground navigational commands to
diverse temporal specifications in 21 city-scaled environments. Finally, we
demonstrate a physical robot using Lang2LTL can follow 52 semantically diverse
navigational commands in two indoor environments.
