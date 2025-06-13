---
layout: publication
title: 'Divide, Reweight, And Conquer: A Logit Arithmetic Approach For In-context Learning'
authors: Chengsong Huang, Langlin Huang, Jiaxin Huang
conference: "Arxiv"
year: 2024
bibkey: huang2024logit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10074"}
tags: ['Efficiency and Optimization', 'Tools', 'RAG', 'Prompting', 'In-Context Learning']
---
In-Context Learning (ICL) emerges as a key feature for Large Language Models
(LLMs), allowing them to adapt to new tasks by leveraging task-specific
examples without updating model parameters. However, ICL faces challenges with
increasing numbers of examples due to performance degradation and quadratic
computational costs. In this paper, we propose Logit Arithmetic Reweighting
Approach (LARA), a novel framework that enhances ICL by using logit-based
ensembling of multiple demonstrations. Our approach divides long input
demonstrations into parallelizable shorter inputs to significantly reduce
memory requirements, and then effectively aggregate the information by
reweighting logits of each group via a non-gradient optimization approach. We
further introduce Binary LARA (B-LARA), a variant that constrains weights to
binary values to simplify the search space and reduces memory usage by
filtering out less informative demonstration groups. Experiments on BBH and
MMLU demonstrate that LARA and B-LARA outperform all baseline methods in both
accuracy and memory efficiency. We also conduct extensive analysis to show that
LARA generalizes well to scenarios of varying numbers of examples from limited
to many-shot demonstrations.
