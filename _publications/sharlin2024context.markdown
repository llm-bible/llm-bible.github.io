---
layout: publication
title: 'In Context Learning And Reasoning For Symbolic Regression With Large Language Models'
authors: Samiha Sharlin, Tyler R. Josephson
conference: "Arxiv"
year: 2024
bibkey: sharlin2024context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17448'}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Tools', 'Prompting', 'Pretraining Methods']
---
Large Language Models (LLMs) are transformer-based machine learning models
that have shown remarkable performance in tasks for which they were not
explicitly trained. Here, we explore the potential of LLMs to perform symbolic
regression -- a machine-learning method for finding simple and accurate
equations from datasets. We prompt GPT-4 to suggest expressions from data,
which are then optimized and evaluated using external Python tools. These
results are fed back to GPT-4, which proposes improved expressions while
optimizing for complexity and loss. Using chain-of-thought prompting, we
instruct GPT-4 to analyze the data, prior expressions, and the scientific
context (expressed in natural language) for each problem before generating new
expressions. We evaluated the workflow in rediscovery of five well-known
scientific equations from experimental data, and on an additional dataset
without a known equation. GPT-4 successfully rediscovered all five equations,
and in general, performed better when prompted to use a scratchpad and consider
scientific context. We demonstrate how strategic prompting improves the model's
performance and how the natural language interface simplifies integrating
theory with data. We also observe how theory can sometimes offset noisy data
and, in other cases, data can make up for poor context. Although this approach
does not outperform established SR programs where target equations are more
complex, LLMs can nonetheless iterate toward improved solutions while following
instructions and incorporating scientific context in natural language.
