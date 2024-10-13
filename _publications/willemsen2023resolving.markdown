---
layout: publication
title: 'Resolving References In Visually-grounded Dialogue Via Text Generation'
authors: Willemsen Bram, Qian Livia, Skantze Gabriel
conference: "Arxiv"
year: 2023
bibkey: willemsen2023resolving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.13430"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Vision-language models (VLMs) have shown to be effective at image retrieval
based on simple text queries, but text-image retrieval based on conversational
input remains a challenge. Consequently, if we want to use VLMs for reference
resolution in visually-grounded dialogue, the discourse processing capabilities
of these models need to be augmented. To address this issue, we propose
fine-tuning a causal large language model (LLM) to generate definite
descriptions that summarize coreferential information found in the linguistic
context of references. We then use a pretrained VLM to identify referents based
on the generated descriptions, zero-shot. We evaluate our approach on a
manually annotated dataset of visually-grounded dialogues and achieve results
that, on average, exceed the performance of the baselines we compare against.
Furthermore, we find that using referent descriptions based on larger context
windows has the potential to yield higher returns.
