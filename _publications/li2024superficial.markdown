---
layout: publication
title: 'Superficial Safety Alignment Hypothesis'
authors: Jianwei Li, Jung-eun Kim
conference: "Arxiv"
year: 2024
bibkey: li2024superficial
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10862'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
As large language models (LLMs) are overwhelmingly more and more integrated
into various applications, ensuring they generate safe and aligned responses is
a pressing need. Previous research on alignment has largely focused on general
instruction-following but has often overlooked the unique properties and
challenges of safety alignment, such as the brittleness of safety mechanisms.
To bridge the gap, we propose the Superficial Safety Alignment Hypothesis
(SSAH), which posits that safety alignment should teach an otherwise unsafe
model to choose the correct reasoning direction - interpreted as a specialized
binary classification task - and incorporate a refusal mechanism with multiple
reserved fallback options. Furthermore, through SSAH, we hypothesize that
safety guardrails in LLMs can be established by just a small number of
essential components. To verify this, we conduct an ablation study and
successfully identify four types of attribute-critical components in
safety-aligned LLMs: Exclusive Safety Unit (ESU), Exclusive Utility Unit (EUU),
Complex Unit (CU), and Redundant Unit (RU). Our findings show that freezing
certain safety-critical components 7.5% during fine-tuning allows the model to
retain its safety attributes while adapting to new tasks. Additionally, we show
that leveraging redundant units 20% in the pre-trained model as an ``alignment
budget'' can effectively minimize the alignment tax while achieving the
alignment goal. All considered, this paper concludes that the atomic functional
unit for safety in LLMs is at the neuron level and underscores that safety
alignment should not be complicated. We believe this work contributes to the
foundation of efficient and scalable safety alignment for future LLMs.
