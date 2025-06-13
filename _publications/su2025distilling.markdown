---
layout: publication
title: 'Distilling Transitional Pattern To Large Language Models For Multimodal Session-based Recommendation'
authors: Jiajie Su, Qiyong Zhong, Yunshan Ma, Weiming Liu, Chaochao Chen, Xiaolin Zheng, Jianwei Yin, Tat-seng Chua
conference: "Arxiv"
year: 2025
bibkey: su2025distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10538"}
tags: ['Efficiency and Optimization', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation']
---
Session-based recommendation (SBR) predicts the next item based on anonymous
sessions. Traditional SBR explores user intents based on ID collaborations or
auxiliary content. To further alleviate data sparsity and cold-start issues,
recent Multimodal SBR (MSBR) methods utilize simplistic pre-trained models for
modality learning but have limitations in semantic richness. Considering
semantic reasoning abilities of Large Language Models (LLM), we focus on the
LLM-enhanced MSBR scenario in this paper, which leverages LLM cognition for
comprehensive multimodal representation generation, to enhance downstream MSBR.
Tackling this problem faces two challenges: i) how to obtain LLM cognition on
both transitional patterns and inherent multimodal knowledge, ii) how to align
both features into one unified LLM, minimize discrepancy while maximizing
representation utility. To this end, we propose a multimodal LLM-enhanced
framework TPAD, which extends a distillation paradigm to decouple and align
transitional patterns for promoting MSBR. TPAD establishes parallel
Knowledge-MLLM and Transfer-MLLM, where the former interprets item
knowledge-reflected features and the latter extracts transition-aware features
underneath sessions. A transitional pattern alignment module harnessing mutual
information estimation theory unites two MLLMs, alleviating distribution
discrepancy and distilling transitional patterns into modal representations.
Extensive experiments on real-world datasets demonstrate the effectiveness of
our framework.
