---
layout: publication
title: 'Self-correction Makes Llms Better Parsers'
authors: Ziyan Zhang, Yang Hou, Chen Gong, Zhenghua Li
conference: "Arxiv"
year: 2025
bibkey: zhang2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14165"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
Large language models (LLMs) have achieved remarkable success across various
natural language processing (NLP) tasks. However, recent studies suggest that
they still face challenges in performing fundamental NLP tasks essential for
deep language understanding, particularly syntactic parsing. In this paper, we
conduct an in-depth analysis of LLM parsing capabilities, delving into the
specific shortcomings of their parsing results. We find that LLMs may stem from
limitations to fully leverage grammar rules in existing treebanks, which
restricts their capability to generate valid syntactic structures. To help LLMs
acquire knowledge without additional training, we propose a self-correction
method that leverages grammar rules from existing treebanks to guide LLMs in
correcting previous errors. Specifically, we automatically detect potential
errors and dynamically search for relevant rules, offering hints and examples
to guide LLMs in making corrections themselves. Experimental results on three
datasets with various LLMs, demonstrate that our method significantly improves
performance in both in-domain and cross-domain settings on the English and
Chinese datasets.
