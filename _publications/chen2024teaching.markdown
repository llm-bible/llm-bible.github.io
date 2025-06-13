---
layout: publication
title: 'Teaching Large Language Models To Express Knowledge Boundary From Their Own Signals'
authors: Lida Chen, Zujie Liang, Xintao Wang, Jiaqing Liang, Yanghua Xiao, Feng Wei, Jinglei Chen, Zhenghong Hao, Bing Han, Wei Wang
conference: "Arxiv"
year: 2024
bibkey: chen2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10881"}
tags: ['RAG', 'Training Techniques']
---
Large language models (LLMs) have achieved great success, but their
occasional content fabrication, or hallucination, limits their practical
application. Hallucination arises because LLMs struggle to admit ignorance due
to inadequate training on knowledge boundaries. We call it a limitation of LLMs
that they can not accurately express their knowledge boundary, answering
questions they know while admitting ignorance to questions they do not know. In
this paper, we aim to teach LLMs to recognize and express their knowledge
boundary, so they can reduce hallucinations caused by fabricating when they do
not know. We propose CoKE, which first probes LLMs' knowledge boundary via
internal confidence given a set of questions, and then leverages the probing
results to elicit the expression of the knowledge boundary. Extensive
experiments show CoKE helps LLMs express knowledge boundaries, answering known
questions while declining unknown ones, significantly improving in-domain and
out-of-domain performance.
