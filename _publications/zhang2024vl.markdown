---
layout: publication
title: 'Vl-uncertainty: Detecting Hallucination In Large Vision-language Model Via Uncertainty Estimation'
authors: Ruiyang Zhang, Hu Zhang, Zhedong Zheng
conference: "Arxiv"
year: 2024
bibkey: zhang2024vl
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.11919'}
tags: ['Prompting', 'Multimodal Models', 'Responsible AI', 'Tools']
---
Given the higher information load processed by large vision-language models
(LVLMs) compared to single-modal LLMs, detecting LVLM hallucinations requires
more human and time expense, and thus rise a wider safety concerns. In this
paper, we introduce VL-Uncertainty, the first uncertainty-based framework for
detecting hallucinations in LVLMs. Different from most existing methods that
require ground-truth or pseudo annotations, VL-Uncertainty utilizes uncertainty
as an intrinsic metric. We measure uncertainty by analyzing the prediction
variance across semantically equivalent but perturbed prompts, including visual
and textual data. When LVLMs are highly confident, they provide consistent
responses to semantically equivalent queries. However, when uncertain, the
responses of the target LVLM become more random. Considering semantically
similar answers with different wordings, we cluster LVLM responses based on
their semantic content and then calculate the cluster distribution entropy as
the uncertainty measure to detect hallucination. Our extensive experiments on
10 LVLMs across four benchmarks, covering both free-form and multi-choice
tasks, show that VL-Uncertainty significantly outperforms strong baseline
methods in hallucination detection.
