---
layout: publication
title: 'Let Your LLM Generate A Few Tokens And You Will Reduce The Need For Retrieval'
authors: Hervé Déjean
conference: "Arxiv"
year: 2024
bibkey: déjean2024let
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.11536'}
tags: ['Reinforcement Learning', 'RAG', 'Security', 'Training Techniques']
---
In this paper, we investigate how efficiently large language models (LLM) can
be trained to check whether an answer is already stored in their parametric
memory. We distill an LLM-as-a-judge to compute the IK (I Know) score. We found
that this method is particularly beneficial in the context of
retrieval-assisted augmented generation (RAG), with a respectable accuracy of
80%. It enables a significant reduction (more than 50%) in the number of search
and reranking steps required for certain data sets. We have also introduced the
IK score, which serves as a useful tool for characterising datasets by
facilitating the classification task. Interestingly, through the inclusion of
response tokens as input, our results suggest that only about 20,000 training
samples are required to achieve good performance. The central element of this
work is the use of a teacher model - the LLM as a judge - to generate training
data. We also assess the robustness of the IK classifier by evaluating it with
various types of teachers, including both string-based methods and LLMs, with
the latter providing better results.
