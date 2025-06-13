---
layout: publication
title: 'How Do Large Language Models Understand Relevance? A Mechanistic Interpretability Perspective'
authors: Qi Liu, Jiaxin Mao, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: liu2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07898"}
tags: ['Applications', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism']
---
Recent studies have shown that large language models (LLMs) can assess
relevance and support information retrieval (IR) tasks such as document ranking
and relevance judgment generation. However, the internal mechanisms by which
off-the-shelf LLMs understand and operationalize relevance remain largely
unexplored. In this paper, we systematically investigate how different LLM
modules contribute to relevance judgment through the lens of mechanistic
interpretability. Using activation patching techniques, we analyze the roles of
various model components and identify a multi-stage, progressive process in
generating either pointwise or pairwise relevance judgment. Specifically, LLMs
first extract query and document information in the early layers, then process
relevance information according to instructions in the middle layers, and
finally utilize specific attention heads in the later layers to generate
relevance judgments in the required format. Our findings provide insights into
the mechanisms underlying relevance assessment in LLMs, offering valuable
implications for future research on leveraging LLMs for IR tasks.
