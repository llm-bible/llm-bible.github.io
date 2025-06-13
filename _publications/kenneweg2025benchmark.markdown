---
layout: publication
title: 'TRAVELER: A Benchmark For Evaluating Temporal Reasoning Across Vague, Implicit And Explicit References'
authors: Svenja Kenneweg, Jörg Deigmöller, Philipp Cimiano, Julian Eggert
conference: "Arxiv"
year: 2025
bibkey: kenneweg2025benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01325"}
tags: ['Applications', 'Survey Paper', 'Reinforcement Learning']
---
Understanding and resolving temporal references is essential in Natural
Language Understanding as we often refer to the past or future in daily
communication. Although existing benchmarks address a system's ability to
reason about and resolve temporal references, systematic evaluation of specific
temporal references remains limited. Towards closing this gap, we introduce
TRAVELER, a novel synthetic benchmark dataset that follows a Question Answering
paradigm and consists of questions involving temporal references with the
corresponding correct answers. TRAVELER assesses models' abilities to resolve
explicit, implicit relative to speech time, and vague temporal references.
Beyond investigating the performance of state-of-the-art LLMs depending on the
type of temporal reference, our benchmark also allows evaluation of performance
in relation to the length of the set of events. For the category of vague
temporal references, ground-truth answers were established via human surveys on
Prolific, following a procedure similar to the one from Kenneweg et al. To
demonstrate the benchmark's applicability, we evaluate four state-of-the-art
LLMs using a question-answering task encompassing 3,300 questions. Our findings
show that while the benchmarked LLMs can answer questions over event sets with
a handful of events and explicit temporal references successfully, performance
clearly deteriorates with larger event set length and when temporal references
get less explicit. Notably, the vague question category exhibits the lowest
performance across all models.
  The benchmark is publicly available at:
https://gitlab.ub.uni-bielefeld.de/s.kenneweg/TRAVELER
