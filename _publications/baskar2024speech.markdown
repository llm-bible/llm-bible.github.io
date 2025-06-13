---
layout: publication
title: 'Speech Prefix-tuning With RNNT Loss For Improving LLM Predictions'
authors: Murali Karthick Baskar, Andrew Rosenberg, Bhuvana Ramabhadran, Neeraj Gaur, Zhong Meng
conference: "Arxiv"
year: 2024
bibkey: baskar2024speech
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.14701'}
tags: ['RAG', 'Prompting']
---
In this paper, we focus on addressing the constraints faced when applying
LLMs to ASR. Recent works utilize prefixLM-type models, which directly apply
speech as a prefix to LLMs for ASR. We have found that optimizing speech
prefixes leads to better ASR performance and propose applying RNNT loss to
perform speech prefix-tuning. This is a simple approach and does not increase
the model complexity or alter the inference pipeline. We also propose
language-based soft prompting to further improve with frozen LLMs. Empirical
analysis on realtime testset from 10 Indic languages demonstrate that our
proposed speech prefix-tuning yields improvements with both frozen and
fine-tuned LLMs. Our recognition results on an average of 10 Indics show that
the proposed prefix-tuning with RNNT loss results in a 12% relative
improvement in WER over the baseline with a fine-tuned LLM. Our proposed
approches with the frozen LLM leads to a 31% relative improvement over basic
soft-prompting prefixLM.
