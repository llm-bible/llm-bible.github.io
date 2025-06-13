---
layout: publication
title: 'Iberbench: LLM Evaluation On Iberian Languages'
authors: José Ángel González, Ian Borrego Obrador, Álvaro Romo Herrero, Areg Mikael Sarvazyan, Mara Chinea-ríos, Angelo Basile, Marc Franco-salvador
conference: "Arxiv"
year: 2025
bibkey: gonzález2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16921"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) remain difficult to evaluate comprehensively,
particularly for languages other than English, where high-quality data is often
limited. Existing benchmarks and leaderboards are predominantly
English-centric, with only a few addressing other languages. These benchmarks
fall short in several key areas: they overlook the diversity of language
varieties, prioritize fundamental Natural Language Processing (NLP)
capabilities over tasks of industrial relevance, and are static. With these
aspects in mind, we present IberBench, a comprehensive and extensible benchmark
designed to assess LLM performance on both fundamental and industry-relevant
NLP tasks, in languages spoken across the Iberian Peninsula and Ibero-America.
IberBench integrates 101 datasets from evaluation campaigns and recent
benchmarks, covering 22 task categories such as sentiment and emotion analysis,
toxicity detection, and summarization. The benchmark addresses key limitations
in current evaluation practices, such as the lack of linguistic diversity and
static evaluation setups by enabling continual updates and community-driven
model and dataset submissions moderated by a committee of experts. We evaluate
23 LLMs ranging from 100 million to 14 billion parameters and provide empirical
insights into their strengths and limitations. Our findings indicate that (i)
LLMs perform worse on industry-relevant tasks than in fundamental ones, (ii)
performance is on average lower for Galician and Basque, (iii) some tasks show
results close to random, and (iv) in other tasks LLMs perform above random but
below shared task systems. IberBench offers open-source implementations for the
entire evaluation pipeline, including dataset normalization and hosting,
incremental evaluation of LLMs, and a publicly accessible leaderboard.
