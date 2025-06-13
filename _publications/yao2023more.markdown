---
layout: publication
title: 'More Samples Or More Prompts? Exploring Effective In-context Sampling For LLM Few-shot Prompt Engineering'
authors: Bingsheng Yao, Guiming Chen, Ruishi Zou, Yuxuan Lu, Jiachen Li, Shao Zhang, Yisi Sang, Sijia Liu, James Hendler, Dakuo Wang
conference: "Arxiv"
year: 2023
bibkey: yao2023more
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09782"}
tags: ['Prompting', 'RAG', 'Few-Shot']
---
While most existing works on LLM prompting techniques focus only on how to
select a better set of data samples inside one single prompt input (In-Context
Learning or ICL), why can not we design and leverage multiple prompts together
to further improve the LLM's performance? In this work, we propose In-Context
Sampling (ICS), a low-resource LLM prompting technique to produce confident
predictions by optimizing the construction of multiple ICL prompt inputs.
Extensive experiments with three open-source LLMs (FlanT5-XL, Mistral-7B, and
Mixtral-8x7B) on four NLI datasets (e-SNLI, Multi-NLI, ANLI, and Contract-NLI)
and one QA dataset (CommonsenseQA) illustrate that ICS can consistently enhance
LLMs' performance. An in-depth evaluation with three data similarity-based ICS
strategies suggests that these strategies can further elevate LLM's
performance, which sheds light on a new yet promising future research
direction.
