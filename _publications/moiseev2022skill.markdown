---
layout: publication
title: SKILL Structured Knowledge Infusion For Large Language Models
authors: Moiseev Fedor, Dong Zhe, Alfonseca Enrique, Jaggi Martin
conference: "Arxiv"
year: 2022
bibkey: moiseev2022skill
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.08184"}
tags: ['Applications', 'Merging', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have demonstrated human-level performance on a vast spectrum of natural language tasks. However it is largely unexplored whether they can better internalize knowledge from a structured data such as a knowledge graph or from text. In this work we propose a method to infuse structured knowledge into LLMs by directly training T5 models on factual triples of knowledge graphs (KGs). We show that models pre-trained on Wikidata KG with our method outperform the T5 baselines on FreebaseQA and WikiHop as well as the Wikidata-answerable subset of TriviaQA and NaturalQuestions. The models pre-trained on factual triples compare competitively with the ones on natural language sentences that contain the same knowledge. Trained on a smaller size KG WikiMovies we saw 3x improvement of exact match score on MetaQA task compared to T5 baseline. The proposed method has an advantage that no alignment between the knowledge graph and text corpus is required in curating training data. This makes our method particularly useful when working with industry-scale knowledge graphs.
