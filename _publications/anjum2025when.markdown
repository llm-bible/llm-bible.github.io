---
layout: publication
title: 'When Reasoning Beats Scale: A 1.5B Reasoning Model Outranks 13B Llms As Discriminator'
authors: Md Fahim Anjum
conference: "Arxiv"
year: 2025
bibkey: anjum2025when
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03786'}
tags: ['Agentic', 'Tools']
---
Large Language Models (LLM) with reasoning capabilities offer a promising
path for improving candidate evaluation in planning frameworks, but their
relative performance against traditional non-reasoning models remains largely
underexplored. In this study, we benchmark a distilled 1.5B parameter reasoning
model (DeepSeek-R1) against several state-of-the-art non-reasoning LLMs within
a generator-discriminator LLM planning framework for the text-to-SQL task. For
this, we introduce a novel method for extracting soft scores from the
chain-of-thought (CoT) outputs from reasoning that enables fine-grained ranking
of candidates. Our central hypothesis is that reasoning models are more
effective discriminators than non-reasoning LLMs. Our results show that
distilled DeepSeek-R1-1.5B achieves up to \\(87%\\) higher F1 and \\(3.7%\\) better
discrimination accuracy than CodeLlama-7B, as well as \\(3.7%\\) higher execution
accuracy than CodeLlama-13B, despite having significantly fewer parameters.
Furthermore, we find that there is a limit to the logical capabilities of
reasoning models, and only providing more context or allowing more compute
budget for reasoning is not enough to improve their discrimination performance.
Finally, we demonstrate that, unlike non-reasoning LLMs, reasoning models find
generation more challenging than discrimination and may underperform as
generators compared to smaller non-reasoning LLMs. Our work highlights the
potential of reasoning models as discriminators in agentic frameworks, far
outweighing their capabilities as generators, offering insights into their
optimal role within LLM planning infrastructures.
