---
layout: publication
title: 'IPAD: Inverse Prompt For AI Detection -- A Robust And Explainable Llm-generated Text Detector'
authors: Zheng Chen, Yushi Feng, Changyang He, Yue Deng, Hongxi Pu, Bo Li
conference: "Arxiv"
year: 2025
bibkey: chen2025inverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15902"}
tags: ['Security', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) have attained human-level fluency in text
generation, which complicates the distinguishing between human-written and
LLM-generated texts. This increases the risk of misuse and highlights the need
for reliable detectors. Yet, existing detectors exhibit poor robustness on
out-of-distribution (OOD) data and attacked data, which is critical for
real-world scenarios. Also, they struggle to provide explainable evidence to
support their decisions, thus undermining the reliability. In light of these
challenges, we propose IPAD (Inverse Prompt for AI Detection), a novel
framework consisting of a Prompt Inverter that identifies predicted prompts
that could have generated the input text, and a Distinguisher that examines how
well the input texts align with the predicted prompts. We develop and examine
two versions of Distinguishers. Empirical evaluations demonstrate that both
Distinguishers perform significantly better than the baseline methods, with
version2 outperforming baselines by 9.73% on in-distribution data (F1-score)
and 12.65% on OOD data (AUROC). Furthermore, a user study is conducted to
illustrate that IPAD enhances the AI detection trustworthiness by allowing
users to directly examine the decision-making evidence, which provides
interpretable support for its state-of-the-art detection results.
