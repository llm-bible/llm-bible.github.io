---
layout: publication
title: 'Unify And Triumph: Polyglot, Diverse, And Self-consistent Generation Of Unit Tests With Llms'
authors: Djamel Eddine Khelladi, Charly Reux, Mathieu Acher
conference: "Arxiv"
year: 2025
bibkey: khelladi2025unify
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16144'}
tags: ['Attention Mechanism', 'RAG', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Large language model (LLM)-based test generation has gained attention in
software engineering, yet most studies evaluate LLMs' ability to generate unit
tests in a single attempt for a given language, missing the opportunity to
leverage LLM diversity for more robust testing. This paper introduces PolyTest,
a novel approach that enhances test generation by exploiting polyglot and
temperature-controlled diversity. PolyTest systematically leverages these
properties in two complementary ways: (1) Cross-lingual test generation, where
tests are generated in multiple languages at zero temperature and then unified;
(2) Diverse test sampling, where multiple test sets are generated within the
same language at a higher temperature before unification. A key insight is that
LLMs can generate diverse yet contradicting tests -- same input, different
expected outputs -- across languages and generations. PolyTest mitigates
inconsistencies by unifying test sets, fostering self-consistency and improving
overall test quality. Unlike single-language or single-attempt approaches,
PolyTest enhances testing without requiring on-the-fly execution, making it
particularly beneficial for weaker-performing languages. We evaluate PolyTest
on Llama3-70B, GPT-4o, and GPT-3.5 using EvalPlus, generating tests in five
languages (Java, C, Python, JavaScript, and a CSV-based format) at temperature
0 and sampling multiple sets at temperature 1. We observe that LLMs frequently
generate contradicting tests across settings, and that PolyTest significantly
improves test quality across all considered metrics -- number of tests, passing
rate, statement/branch coverage (up to +9.01%), and mutation score (up to
+11.23%). Finally, PolyTest outperforms Pynguin in test generation, passing
rate, and mutation score.
