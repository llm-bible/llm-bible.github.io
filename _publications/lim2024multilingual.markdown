---
layout: publication
title: 'Mufu: Multilingual Fused Learning For Low-resource Translation With LLM'
authors: Zheng Wei Lim, Nitish Gupta, Honglin Yu, Trevor Cohn
conference: "Arxiv"
year: 2024
bibkey: lim2024multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.13949'}
tags: ['RAG', 'Efficiency and Optimization', 'Prompting']
---
Multilingual large language models (LLMs) are great translators, but this is
largely limited to high-resource languages. For many LLMs, translating in and
out of low-resource languages remains a challenging task. To maximize data
efficiency in this low-resource setting, we introduce Mufu, which includes a
selection of automatically generated multilingual candidates and an instruction
to correct inaccurate translations in the prompt. Mufu prompts turn a
translation task into a postediting one, and seek to harness the LLM's
reasoning capability with auxiliary translation candidates, from which the
model is required to assess the input quality, align the semantics
cross-lingually, copy from relevant inputs and override instances that are
incorrect. Our experiments on En-XX translations over the Flores-200 dataset
show LLMs finetuned against Mufu-style prompts are robust to poor quality
auxiliary translation candidates, achieving performance superior to NLLB 1.3B
distilled model in 64% of low- and very-low-resource language pairs. We then
distill these models to reduce inference cost, while maintaining on average 3.1
chrF improvement over finetune-only baseline in low-resource translations.
