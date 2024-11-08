---
layout: publication
title: 'Scimon: Scientific Inspiration Machines Optimized For Novelty'
authors: Wang Qingyun, Downey Doug, Ji Heng, Hope Tom
conference: "Arxiv"
year: 2023
bibkey: wang2023scientific
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14259"}
tags: ['GPT', 'Model Architecture', 'Tools']
---
We explore and enhance the ability of neural language models to generate
novel scientific directions grounded in literature. Work on literature-based
hypothesis generation has traditionally focused on binary link
prediction--severely limiting the expressivity of hypotheses. This line of work
also does not focus on optimizing novelty. We take a dramatic departure with a
novel setting in which models use as input background contexts (e.g., problems,
experimental settings, goals), and output natural language ideas grounded in
literature. We present SciMON, a modeling framework that uses retrieval of
"inspirations" from past scientific papers, and explicitly optimizes for
novelty by iteratively comparing to prior papers and updating idea suggestions
until sufficient novelty is achieved. Comprehensive evaluations reveal that
GPT-4 tends to generate ideas with overall low technical depth and novelty,
while our methods partially mitigate this issue. Our work represents a first
step toward evaluating and developing language models that generate new ideas
derived from the scientific literature
