---
layout: publication
title: 'The Factuality Tax Of Diversity-intervened Text-to-image Generation: Benchmark And Fact-augmented Intervention'
authors: Yixin Wan, Di Wu, Haoran Wang, Kai-wei Chang
conference: "Arxiv"
year: 2024
bibkey: wan2024factuality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00377"}
tags: ['Prompting', 'Reinforcement Learning']
---
Prompt-based "diversity interventions" are commonly adopted to improve the
diversity of Text-to-Image (T2I) models depicting individuals with various
racial or gender traits. However, will this strategy result in nonfactual
demographic distribution, especially when generating real historical figures.
In this work, we propose DemOgraphic FActualIty Representation (DoFaiR), a
benchmark to systematically quantify the trade-off between using diversity
interventions and preserving demographic factuality in T2I models. DoFaiR
consists of 756 meticulously fact-checked test instances to reveal the
factuality tax of various diversity prompts through an automated
evidence-supported evaluation pipeline. Experiments on DoFaiR unveil that
diversity-oriented instructions increase the number of different gender and
racial groups in DALLE-3's generations at the cost of historically inaccurate
demographic distributions. To resolve this issue, we propose Fact-Augmented
Intervention (FAI), which instructs a Large Language Model (LLM) to reflect on
verbalized or retrieved factual information about gender and racial
compositions of generation subjects in history, and incorporate it into the
generation context of T2I models. By orienting model generations using the
reflected historical truths, FAI significantly improves the demographic
factuality under diversity interventions while preserving diversity.
