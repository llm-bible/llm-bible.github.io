---
layout: publication
title: 'GRAIT: Gradient-driven Refusal-aware Instruction Tuning For Effective Hallucination Mitigation'
authors: Runchuan Zhu, Zinco Jiang, Jiang Wu, Zhipeng Ma, Jiahe Song, Fengshuo Bai, Dahua Lin, Lijun Wu, Conghui He
conference: "Arxiv"
year: 2025
bibkey: zhu2025gradient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.05911'}
  - {name: "Code", url: 'https://github.com/opendatalab/GRAIT'}
tags: ['Has Code', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Refusal-Aware Instruction Tuning (RAIT) aims to enhance Large Language Models
(LLMs) by improving their ability to refuse responses to questions beyond their
knowledge, thereby reducing hallucinations and improving reliability. Effective
RAIT must address two key challenges: firstly, effectively reject unknown
questions to minimize hallucinations; secondly, avoid over-refusal to ensure
questions that can be correctly answered are not rejected, thereby maintain the
helpfulness of LLM outputs. In this paper, we address the two challenges by
deriving insightful observations from the gradient-based perspective, and
proposing the Gradient-driven Refusal Aware Instruction Tuning Framework GRAIT:
(1) employs gradient-driven sample selection to effectively minimize
hallucinations and (2) introduces an adaptive weighting mechanism during
fine-tuning to reduce the risk of over-refusal, achieving the balance between
accurate refusals and maintaining useful responses. Experimental evaluations on
open-ended and multiple-choice question answering tasks demonstrate that GRAIT
significantly outperforms existing RAIT methods in the overall performance. The
source code and data will be available at https://github.com/opendatalab/GRAIT .
