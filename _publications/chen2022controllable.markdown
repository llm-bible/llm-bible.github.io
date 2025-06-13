---
layout: publication
title: 'Controllable Text Generation With Language Constraints'
authors: Howard Chen, Huihan Li, Danqi Chen, Karthik Narasimhan
conference: "Arxiv"
year: 2022
bibkey: chen2022controllable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.10466'}
tags: ['Language Modeling', 'RAG', 'GPT', 'Applications', 'Model Architecture']
---
We consider the task of text generation in language models with constraints
specified in natural language. To this end, we first create a challenging
benchmark Cognac that provides as input to the model a topic with example text,
along with a constraint on text to be avoided. Unlike prior work, our benchmark
contains knowledge-intensive constraints sourced from databases like Wordnet
and Wikidata, which allows for straightforward evaluation while striking a
balance between broad attribute-level and narrow lexical-level controls. We
find that even state-of-the-art language models like GPT-3 fail often on this
task, and propose a solution to leverage a language model's own internal
knowledge to guide generation. Our method, called CognacGen, first queries the
language model to generate guidance terms for a specified topic or constraint,
and uses the guidance to modify the model's token generation probabilities. We
propose three forms of guidance (binary verifier, top-k tokens, textual
example), and employ prefix-tuning approaches to distill the guidance to tackle
diverse natural language constraints. Through extensive empirical evaluations,
we demonstrate that CognacGen can successfully generalize to unseen
instructions and outperform competitive baselines in generating constraint
conforming text.
