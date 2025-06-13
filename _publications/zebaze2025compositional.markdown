---
layout: publication
title: 'Compositional Translation: A Novel Llm-based Approach For Low-resource Machine Translation'
authors: Armel Zebaze, Benoît Sagot, Rachel Bawden
conference: "Arxiv"
year: 2025
bibkey: zebaze2025compositional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04554"}
  - {name: "Code", url: "https://github.com/ArmelRandy/compositional-translation"}
tags: ['Few-Shot', 'Has Code', 'Prompting', 'Applications']
---
The ability of generative large language models (LLMs) to perform in-context
learning has given rise to a large body of research into how best to prompt
models for various natural language processing tasks. Machine Translation (MT)
has been shown to benefit from in-context examples, in particular when they are
semantically similar to the sentence to translate. In this paper, we propose a
new LLM-based translation paradigm, compositional translation, to replace naive
few-shot MT with similarity-based demonstrations. An LLM is used to decompose a
sentence into simpler phrases, and then to translate each phrase with the help
of retrieved demonstrations. Finally, the LLM is prompted to translate the
initial sentence with the help of the self-generated phrase-translation pairs.
Our intuition is that this approach should improve translation because these
shorter phrases should be intrinsically easier to translate and easier to match
with relevant examples. This is especially beneficial in low-resource
scenarios, and more generally whenever the selection pool is small or out of
domain. We show that compositional translation boosts LLM translation
performance on a wide range of popular MT benchmarks, including FLORES 200,
NTREX 128 and TICO-19. Code and outputs are available at
https://github.com/ArmelRandy/compositional-translation
