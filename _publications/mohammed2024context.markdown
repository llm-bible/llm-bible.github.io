---
layout: publication
title: 'Context-aware Or Context-insensitive? Assessing Llms'' Performance In Document-level Translation'
authors: Wafaa Mohammed, Vlad Niculae
conference: "Arxiv"
year: 2024
bibkey: mohammed2024context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14391'}
tags: ['Transformer', 'Security', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
Large language models (LLMs) are increasingly strong contenders in machine
translation. In this work, we focus on document-level translation, where some
words cannot be translated without context from outside the sentence.
Specifically, we investigate the ability of prominent LLMs to utilize the
document context during translation through a perturbation analysis (analyzing
models' robustness to perturbed and randomized document context) and an
attribution analysis (examining the contribution of relevant context to the
translation). We conduct an extensive evaluation across nine LLMs from diverse
model families and training paradigms, including translation-specialized LLMs,
alongside two encoder-decoder transformer baselines. We find that LLMs'
improved document-translation performance compared to encoder-decoder models is
not reflected in pronoun translation performance. Our analysis highlight the
need for context-aware finetuning of LLMs with a focus on relevant parts of the
context to improve their reliability for document-level translation.
