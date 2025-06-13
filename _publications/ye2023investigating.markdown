---
layout: publication
title: 'Investigating The Effectiveness Of Task-agnostic Prefix Prompt For Instruction Following'
authors: Seonghyeon Ye, Hyeonbin Hwang, Sohee Yang, Hyeongu Yun, Yireun Kim, Minjoon Seo
conference: "Arxiv"
year: 2023
bibkey: ye2023investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2302.14691'}
  - {name: "Code", url: 'https://github.com/seonghyeonye/TAPP'}
tags: ['RAG', 'Has Code', 'Prompting']
---
In this paper, we present our finding that prepending a Task-Agnostic Prefix
Prompt (TAPP) to the input improves the instruction-following ability of
various Large Language Models (LLMs) during inference. TAPP is different from
canonical prompts for LLMs in that it is a fixed prompt prepended to the
beginning of every input regardless of the target task for zero-shot
generalization. We observe that both base LLMs (i.e. not fine-tuned to follow
instructions) and instruction-tuned models benefit from TAPP, resulting in
34.58% and 12.26% improvement on average, respectively. This implies that the
instruction-following ability of LLMs can be improved during inference time
with a fixed prompt constructed with simple heuristics. We hypothesize that
TAPP assists language models to better estimate the output distribution by
focusing more on the instruction of the target task during inference. In other
words, such ability does not seem to be sufficiently activated in not only base
LLMs but also many instruction-fine-tuned LLMs. All experiments are
reproducible from https://github.com/seonghyeonye/TAPP.
