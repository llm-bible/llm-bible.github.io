---
layout: publication
title: 'GPT-RE: In-context Learning For Relation Extraction Using Large Language Models'
authors: Zhen Wan et al.
conference: Arxiv
year: 2023
citations: 60
bibkey: wan2023gpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.02105'}]
tags: [In-Context Learning, GPT, BERT]
---
In spite of the potential for ground-breaking achievements offered by large
language models (LLMs) (e.g., GPT-3), they still lag significantly behind
fully-supervised baselines (e.g., fine-tuned BERT) in relation extraction (RE).
This is due to the two major shortcomings of LLMs in RE: (1) low relevance
regarding entity and relation in retrieved demonstrations for in-context
learning; and (2) the strong inclination to wrongly classify NULL examples into
other pre-defined labels.
  In this paper, we propose GPT-RE to bridge the gap between LLMs and
fully-supervised baselines. GPT-RE successfully addresses the aforementioned
issues by (1) incorporating task-specific entity representations in
demonstration retrieval; and (2) enriching the demonstrations with gold
label-induced reasoning logic. We evaluate GPT-RE on four widely-used RE
datasets, and observe that GPT-RE achieves improvements over not only existing
GPT-3 baselines, but also fully-supervised baselines. Specifically, GPT-RE
achieves SOTA performances on the Semeval and SciERC datasets, and competitive
performances on the TACRED and ACE05 datasets.