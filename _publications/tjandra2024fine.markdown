---
layout: publication
title: 'Fine-tuning Large Language Models To Appropriately Abstain With Semantic Entropy'
authors: Benedict Aaron Tjandra, Muhammed Razzak, Jannik Kossen, Kunal Handa, Yarin Gal
conference: "Arxiv"
year: 2024
bibkey: tjandra2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17234'}
tags: ['Training Techniques', 'Fine-Tuning', 'Applications', 'Pretraining Methods']
---
Large Language Models (LLMs) are known to hallucinate, whereby they generate
plausible but inaccurate text. This phenomenon poses significant risks in
critical applications, such as medicine or law, necessitating robust
hallucination mitigation strategies. While recent works have proposed
fine-tuning methods to teach LLMs to abstain from answering questions beyond
their knowledge or capabilities, these methods rely on the existence of
ground-truth labels or are limited to short-form responses. To address these
limitations, we propose fine-tuning using semantic entropy, an uncertainty
measure derived from introspection into the model which does not require
external labels. We demonstrate that our approach matches or outperforms models
fine-tuned using prior work and achieves strong performance for both short and
long-form generations on a range of datasets.
