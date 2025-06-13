---
layout: publication
title: 'Bridging The Gap Between Different Vocabularies For LLM Ensemble'
authors: Yangyifan Xu, Jinliang Lu, Jiajun Zhang
conference: "Arxiv"
year: 2024
bibkey: xu2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09492"}
tags: ['RAG', 'Reinforcement Learning', 'Language Modeling', 'Applications']
---
Ensembling different large language models (LLMs) to unleash their
complementary potential and harness their individual strengths is highly
valuable. Nevertheless, vocabulary discrepancies among various LLMs have
constrained previous studies to either selecting or blending completely
generated outputs. This limitation hinders the dynamic correction and
enhancement of outputs during the generation process, resulting in a limited
capacity for effective ensemble. To address this issue, we propose a novel
method to Ensemble LLMs via Vocabulary Alignment (EVA). EVA bridges the lexical
gap among various LLMs, enabling meticulous ensemble at each generation step.
Specifically, we first learn mappings between the vocabularies of different
LLMs with the assistance of overlapping tokens. Subsequently, these mappings
are employed to project output distributions of LLMs into a unified space,
facilitating a fine-grained ensemble. Finally, we design a filtering strategy
to exclude models that generate unfaithful tokens. Experimental results on
commonsense reasoning, arithmetic reasoning, machine translation, and
data-to-text generation tasks demonstrate the superiority of our approach
compared with individual LLMs and previous ensemble methods conducted on
complete outputs. Further analyses confirm that our approach can leverage
knowledge from different language models and yield consistent improvement.
