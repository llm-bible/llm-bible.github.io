---
layout: publication
title: 'Assessing The Interpretability Of Programmatic Policies With Large Language Models'
authors: Zahra Bashir, Michael Bowling, Levi H. S. Lelis
conference: "Arxiv"
year: 2023
bibkey: bashir2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06979"}
tags: ['Interpretability and Explainability']
---
Although the synthesis of programs encoding policies often carries the
promise of interpretability, systematic evaluations were never performed to
assess the interpretability of these policies, likely because of the complexity
of such an evaluation. In this paper, we introduce a novel metric that uses
large-language models (LLM) to assess the interpretability of programmatic
policies. For our metric, an LLM is given both a program and a description of
its associated programming language. The LLM then formulates a natural language
explanation of the program. This explanation is subsequently fed into a second
LLM, which tries to reconstruct the program from the natural-language
explanation. Our metric then measures the behavioral similarity between the
reconstructed program and the original. We validate our approach with
synthesized and human-crafted programmatic policies for playing a real-time
strategy game, comparing the interpretability scores of these programmatic
policies to obfuscated versions of the same programs. Our LLM-based
interpretability score consistently ranks less interpretable programs lower and
more interpretable ones higher. These findings suggest that our metric could
serve as a reliable and inexpensive tool for evaluating the interpretability of
programmatic policies.
