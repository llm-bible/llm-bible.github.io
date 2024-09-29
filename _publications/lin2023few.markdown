---
layout: publication
title: Few45;shot Adaptation For Parsing Contextual Utterances With Llms
authors: Lin Kevin, Xia Patrick, Fang Hao
conference: "Arxiv"
year: 2023
bibkey: lin2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10168"}
tags: ['Prompting', 'Reinforcement Learning', 'Training Techniques']
---
We evaluate the ability of semantic parsers based on large language models (LLMs) to handle contextual utterances. In real45;world settings there typically exists only a limited number of annotated contextual utterances due to annotation cost resulting in an imbalance compared to non45;contextual utterances. Therefore parsers must adapt to contextual utterances with a few training examples. We examine four major paradigms for doing so in conversational semantic parsing i.e. Parse45;with45;Utterance45;History Parse45;with45;Reference45;Program Parse45;then45;Resolve and Rewrite45;then45;Parse. To facilitate such cross45;paradigm comparisons we construct SMCalFlow45;EventQueries a subset of contextual examples from SMCalFlow with additional annotations. Experiments with in45;context learning and fine45;tuning suggest that Rewrite45;then45;Parse is the most promising paradigm when holistically considering parsing accuracy annotation cost and error types.
