---
layout: publication
title: 'How Can We Effectively Expand The Vocabulary Of Llms With 0.01GB Of Target Language Text?'
authors: Atsuki Yamaguchi, Aline Villavicencio, Nikolaos Aletras
conference: "Arxiv"
year: 2024
bibkey: yamaguchi2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11477"}
tags: ['Training Techniques', 'Pre-Training', 'Efficiency and Optimization']
---
Large language models (LLMs) have shown remarkable capabilities in many
languages beyond English. Yet, LLMs require more inference steps when
generating non-English text due to their reliance on English-centric tokenizers
and vocabulary, resulting in higher usage costs to non-English speakers.
Vocabulary expansion with target language tokens is a widely used cross-lingual
vocabulary adaptation approach to remedy this issue. Despite its effectiveness
in inference speedup, previous work on vocabulary expansion has focused on
high-resource settings assuming access to a substantial amount of target
language data to effectively initialize the embeddings of the new tokens and
adapt the LLM to the target language. However, vocabulary expansion in
low-resource settings has yet to be explored. In this paper, we investigate
vocabulary expansion in low-resource settings by considering embedding
initialization methods and continual pre-training strategies. Through extensive
experiments across typologically diverse languages, tasks and models, we
establish a set of strategies to perform vocabulary expansion for faster
inference, maintaining competitive downstream performance to baselines with
only 30K sentences (\\(\sim\\)0.01GB text data) from the target language.
