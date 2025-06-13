---
layout: publication
title: 'Holistic Audit Dataset Generation For LLM Unlearning Via Knowledge Graph Traversal And Redundancy Removal'
authors: Weipeng Jiang, Juan Zhai, Shiqing Ma, Ziyan Lei, Xiaofei Xie, Yige Wang, Chao Shen
conference: "Arxiv"
year: 2025
bibkey: jiang2025holistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18810"}
tags: ['RAG', 'Applications', 'Tools']
---
In recent years, Large Language Models (LLMs) have faced increasing demands
to selectively remove sensitive information, protect privacy, and comply with
copyright regulations through unlearning, by Machine Unlearning. While
evaluating unlearning effectiveness is crucial, existing benchmarks are limited
in scale and comprehensiveness, typically containing only a few hundred test
cases. We identify two critical challenges in generating holistic audit
datasets: ensuring audit adequacy and handling knowledge redundancy between
forget and retain dataset. To address these challenges, we propose HANKER, an
automated framework for holistic audit dataset generation leveraging knowledge
graphs to achieve fine-grained coverage and eliminate redundant knowledge.
Applying HANKER to the popular MUSE benchmark, we successfully generated over
69,000 and 111,000 audit cases for the News and Books datasets respectively,
identifying thousands of knowledge memorization instances that the previous
benchmark failed to detect. Our empirical analysis uncovers how knowledge
redundancy significantly skews unlearning effectiveness metrics, with redundant
instances artificially inflating the observed memorization measurements ROUGE
from 19.7% to 26.1% and Entailment Scores from 32.4% to 35.2%, highlighting the
necessity of systematic deduplication for accurate assessment.
