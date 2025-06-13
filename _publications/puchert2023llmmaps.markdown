---
layout: publication
title: 'Llmmaps -- A Visual Metaphor For Stratified Evaluation Of Large Language Models'
authors: Patrik Puchert, Poonam Poonam, Christian Van Onzenoodt, Timo Ropinski
conference: "Arxiv"
year: 2023
bibkey: puchert2023llmmaps
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.00457"}
  - {name: "Code", url: "https://github.com/viscom-ulm/LLMMaps"}
tags: ['Model Architecture', 'Reinforcement Learning', 'GPT', 'Ethics and Bias', 'Interpretability', 'Has Code']
---
Large Language Models (LLMs) have revolutionized natural language processing
and demonstrated impressive capabilities in various tasks. Unfortunately, they
are prone to hallucinations, where the model exposes incorrect or false
information in its responses, which renders diligent evaluation approaches
mandatory. While LLM performance in specific knowledge fields is often
evaluated based on question and answer (Q&A) datasets, such evaluations usually
report only a single accuracy number for the dataset, which often covers an
entire field. This field-based evaluation, is problematic with respect to
transparency and model improvement. A stratified evaluation could instead
reveal subfields, where hallucinations are more likely to occur and thus help
to better assess LLMs' risks and guide their further development. To support
such stratified evaluations, we propose LLMMaps as a novel visualization
technique that enables users to evaluate LLMs' performance with respect to Q&A
datasets. LLMMaps provide detailed insights into LLMs' knowledge capabilities
in different subfields, by transforming Q&A datasets as well as LLM responses
into an internal knowledge structure. An extension for comparative
visualization furthermore, allows for the detailed comparison of multiple LLMs.
To assess LLMMaps we use them to conduct a comparative analysis of several
state-of-the-art LLMs, such as BLOOM, GPT-2, GPT-3, ChatGPT and LLaMa-13B, as
well as two qualitative user evaluations. All necessary source code and data
for generating LLMMaps to be used in scientific publications and elsewhere is
available on GitHub: https://github.com/viscom-ulm/LLMMaps
