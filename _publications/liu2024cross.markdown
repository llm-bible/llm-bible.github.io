---
layout: publication
title: 'Chatzero:zero-shot Cross-lingual Dialogue Generation Via Pseudo-target Language'
authors: Liu Yongkang, Shi Feng, Wang Daling, Zhang Yifei, Schütze Hinrich
conference: "ECAI"
year: 2024
bibkey: liu2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08724"}
tags: ['Applications', 'Pretraining Methods']
---
Although large language models(LLMs) show amazing capabilities, among various
exciting applications discovered for LLMs fall short in other low-resource
languages. Besides, most existing methods depend on large-scale dialogue
corpora and thus building systems for dialogue generation in a zero-shot
scenario remains a considerable challenge. To address this challenge, we
propose a novel end-to-end zero-shot dialogue generation model ChatZero based
on cross-lingual code-switching method. First, we construct code-switching
language and pseudo-target language with placeholders. Then for cross-lingual
semantic transfer, we employ unsupervised contrastive learning to minimize the
semantics gap of the source language, code-switching language, and
pseudo-target language that are mutually positive examples in the high
dimensional semantic space. Experiments on the multilingual DailyDialog and
DSTC7-AVSD datasets demonstrate that ChatZero can achieve more than 90\% of the
original performance under the zero-shot case compared to supervised learning,
and achieve state-of-the-art performance compared with other baselines.
