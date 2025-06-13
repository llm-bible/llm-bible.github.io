---
layout: publication
title: 'Llava-surg: Towards Multimodal Surgical Assistant Via Structured Surgical Video Learning'
authors: Jiajie Li, Garrett Skinner, Gene Yang, Brian R Quaranto, Steven D Schwaitzberg, Peter C W Kim, Jinjun Xiong
conference: "Arxiv"
year: 2024
bibkey: li2024llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07981"}
tags: ['Multimodal Models', 'Fine-Tuning']
---
Multimodal large language models (LLMs) have achieved notable success across
various domains, while research in the medical field has largely focused on
unimodal images. Meanwhile, current general-domain multimodal models for videos
still lack the capabilities to understand and engage in conversations about
surgical videos. One major contributing factor is the absence of datasets in
the surgical field. In this paper, we create a new dataset, Surg-QA, consisting
of 102,000 surgical video-instruction pairs, the largest of its kind so far. To
build such a dataset, we propose a novel two-stage question-answer generation
pipeline with LLM to learn surgical knowledge in a structured manner from the
publicly available surgical lecture videos. The pipeline breaks down the
generation process into two stages to significantly reduce the task complexity,
allowing us to use a more affordable, locally deployed open-source LLM than the
premium paid LLM services. It also mitigates the risk of LLM hallucinations
during question-answer generation, thereby enhancing the overall quality of the
generated data. We further train LLaVA-Surg, a novel vision-language
conversational assistant capable of answering open-ended questions about
surgical videos, on this Surg-QA dataset, and conduct comprehensive evaluations
on zero-shot surgical video question-answering tasks. We show that LLaVA-Surg
significantly outperforms all previous general-domain models, demonstrating
exceptional multimodal conversational skills in answering open-ended questions
about surgical videos. We will release our code, model, and the
instruction-tuning dataset.
