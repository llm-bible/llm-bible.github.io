---
layout: publication
title: 'RECALL: Library-like Behavior In Language Models Is Enhanced By Self-referencing Causal Cycles'
authors: Munachiso Nwadike, Zangir Iklassov, Toluwani Aremu, Tatsuya Hiraoka, Velibor Bojkovic, Benjamin Heinzerling, Hilal Alqaubeh, Martin Takáč, Kentaro Inui
conference: "Arxiv"
year: 2025
bibkey: nwadike2025library
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.13491'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/remember-B0B8/'}
tags: ['Has Code', 'ACL', 'Training Techniques', 'GPT', 'Model Architecture', 'Tools', 'Prompting', 'Reinforcement Learning', 'TACL']
---
We introduce the concept of the self-referencing causal cycle (abbreviated
RECALL) - a mechanism that enables large language models (LLMs) to bypass the
limitations of unidirectional causality, which underlies a phenomenon known as
the reversal curse. When an LLM is prompted with sequential data, it often
fails to recall preceding context. For example, when we ask an LLM to recall
the line preceding "O say does that star-spangled banner yet wave" in the U.S.
National Anthem, it often fails to correctly return "Gave proof through the
night that our flag was still there" - this is due to the reversal curse. It
occurs because language models such as ChatGPT and Llama generate text based on
preceding tokens, requiring facts to be learned and reproduced in a consistent
token order. While the reversal curse is often viewed as a limitation, we offer
evidence of an alternative view: it is not always an obstacle in practice. We
find that RECALL is driven by what we designate as cycle tokens - sequences
that connect different parts of the training data, enabling recall of preceding
tokens from succeeding ones. Through rigorous probabilistic formalization and
controlled experiments, we demonstrate how the cycles they induce influence a
model's ability to reproduce information. To facilitate reproducibility, we
provide our code and experimental details at
https://anonymous.4open.science/r/remember-B0B8/.
