---
layout: publication
title: 'Few-shot Adaptation For Parsing Contextual Utterances With Llms'
authors: Kevin Lin, Patrick Xia, Hao Fang
conference: "Arxiv"
year: 2023
bibkey: lin2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10168"}
tags: ['Training Techniques', 'Few-Shot', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
We evaluate the ability of semantic parsers based on large language models
(LLMs) to handle contextual utterances. In real-world settings, there typically
exists only a limited number of annotated contextual utterances due to
annotation cost, resulting in an imbalance compared to non-contextual
utterances. Therefore, parsers must adapt to contextual utterances with a few
training examples. We examine four major paradigms for doing so in
conversational semantic parsing i.e., Parse-with-Utterance-History,
Parse-with-Reference-Program, Parse-then-Resolve, and Rewrite-then-Parse. To
facilitate such cross-paradigm comparisons, we construct
SMCalFlow-EventQueries, a subset of contextual examples from SMCalFlow with
additional annotations. Experiments with in-context learning and fine-tuning
suggest that Rewrite-then-Parse is the most promising paradigm when
holistically considering parsing accuracy, annotation cost, and error types.
