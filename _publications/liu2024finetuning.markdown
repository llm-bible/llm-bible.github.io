---
layout: publication
title: 'Finetuning Generative Large Language Models With Discrimination Instructions For Knowledge Graph Completion'
authors: Yang Liu, Xiaobin Tian, Zequn Sun, Wei Hu
conference: "Arxiv"
year: 2024
bibkey: liu2024finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16127"}
tags: ['Tools', 'Applications']
---
Traditional knowledge graph (KG) completion models learn embeddings to
predict missing facts. Recent works attempt to complete KGs in a
text-generation manner with large language models (LLMs). However, they need to
ground the output of LLMs to KG entities, which inevitably brings errors. In
this paper, we present a finetuning framework, DIFT, aiming to unleash the KG
completion ability of LLMs and avoid grounding errors. Given an incomplete
fact, DIFT employs a lightweight model to obtain candidate entities and
finetunes an LLM with discrimination instructions to select the correct one
from the given candidates. To improve performance while reducing instruction
data, DIFT uses a truncated sampling method to select useful facts for
finetuning and injects KG embeddings into the LLM. Extensive experiments on
benchmark datasets demonstrate the effectiveness of our proposed framework.
