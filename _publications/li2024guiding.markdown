---
layout: publication
title: 'Guiding Enumerative Program Synthesis With Large Language Models'
authors: Yixuan Li, Julian Parsert, Elizabeth Polgreen
conference: "Arxiv"
year: 2024
bibkey: li2024guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03997"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Prompting']
---
Pre-trained Large Language Models (LLMs) are beginning to dominate the
discourse around automatic code generation with natural language
specifications. In contrast, the best-performing synthesizers in the domain of
formal synthesis with precise logical specifications are still based on
enumerative algorithms. In this paper, we evaluate the abilities of LLMs to
solve formal synthesis benchmarks by carefully crafting a library of prompts
for the domain. When one-shot synthesis fails, we propose a novel enumerative
synthesis algorithm, which integrates calls to an LLM into a weighted
probabilistic search. This allows the synthesizer to provide the LLM with
information about the progress of the enumerator, and the LLM to provide the
enumerator with syntactic guidance in an iterative loop. We evaluate our
techniques on benchmarks from the Syntax-Guided Synthesis (SyGuS) competition.
We find that GPT-3.5 as a stand-alone tool for formal synthesis is easily
outperformed by state-of-the-art formal synthesis algorithms, but our approach
integrating the LLM into an enumerative synthesis algorithm shows significant
performance gains over both the LLM and the enumerative synthesizer alone and
the winning SyGuS competition tool.
