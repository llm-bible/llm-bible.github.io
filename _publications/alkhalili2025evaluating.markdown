---
layout: publication
title: 'Evaluating Grounded Reasoning By Code-assisted Large Language Models For Mathematics'
authors: Zena Al-khalili, Nick Howell, Dietrich Klakow
conference: "Arxiv"
year: 2025
bibkey: alkhalili2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17665"}
tags: ['Applications']
---
Assisting LLMs with code generation improved their performance on
mathematical reasoning tasks. However, the evaluation of code-assisted LLMs is
generally restricted to execution correctness, lacking a rigorous evaluation of
their generated programs. In this work, we bridge this gap by conducting an
in-depth analysis of code-assisted LLMs' generated programs in response to math
reasoning tasks. Our evaluation focuses on the extent to which LLMs ground
their programs to math rules, and how that affects their end performance. For
this purpose, we assess the generations of five different LLMs, on two
different math datasets, both manually and automatically. Our results reveal
that the distribution of grounding depends on LLMs' capabilities and the
difficulty of math problems. Furthermore, mathematical grounding is more
effective for closed-source models, while open-source models fail to employ
math rules in their solutions correctly. On MATH500, the percentage of grounded
programs decreased to half, while the ungrounded generations doubled in
comparison to ASDiv grade-school problems. Our work highlights the need for
in-depth evaluation beyond execution accuracy metrics, toward a better
understanding of code-assisted LLMs' capabilities and limits in the math
domain.
