---
layout: publication
title: 'Localizing Factual Inconsistencies In Attributable Text Generation'
authors: Arie Cattan, Paul Roit, Shiyue Zhang, David Wan, Roee Aharoni, Idan Szpektor, Mohit Bansal, Ido Dagan
conference: "Arxiv"
year: 2024
bibkey: cattan2024localizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.07473'}
tags: ['Reinforcement Learning', 'Language Modeling', 'Applications']
---
There has been an increasing interest in detecting hallucinations in
model-generated texts, both manually and automatically, at varying levels of
granularity. However, most existing methods fail to precisely pinpoint the
errors. In this work, we introduce QASemConsistency, a new formalism for
localizing factual inconsistencies in attributable text generation, at a
fine-grained level. Drawing inspiration from Neo-Davidsonian formal semantics,
we propose decomposing the generated text into minimal predicate-argument level
propositions, expressed as simple question-answer (QA) pairs, and assess
whether each individual QA pair is supported by a trusted reference text. As
each QA pair corresponds to a single semantic relation between a predicate and
an argument, QASemConsistency effectively localizes the unsupported
information. We first demonstrate the effectiveness of the QASemConsistency
methodology for human annotation, by collecting crowdsourced annotations of
granular consistency errors, while achieving a substantial inter-annotator
agreement (\\(\kappa > 0.7)\\). Then, we implement several methods for
automatically detecting localized factual inconsistencies, with both supervised
entailment models and open-source LLMs.
