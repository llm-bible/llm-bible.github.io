---
layout: publication
title: 'Tiebe: Tracking Language Model Recall Of Notable Worldwide Events Through Time'
authors: Thales Sales Almeida, Giovana Kerche Bonás, João Guilherme Alves Santos, Hugo Abonizio, Rodrigo Nogueira
conference: "Arxiv"
year: 2025
bibkey: almeida2025tracking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.07482'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques']
---
As the knowledge landscape evolves and large language models (LLMs) become increasingly widespread, there is a growing need to keep these models updated with current events. While existing benchmarks assess general factual recall, few studies explore how LLMs retain knowledge over time or across different regions. To address these gaps, we present the Timely Events Benchmark (TiEBe), a dataset of over 23,000 question-answer pairs centered on notable global and regional events, spanning more than 10 years of events, 23 regions, and 13 languages. TiEBe leverages structured retrospective data from Wikipedia to identify notable events through time. These events are then used to construct a benchmark to evaluate LLMs' understanding of global and regional developments, grounded in factual evidence beyond Wikipedia itself. Our results reveal significant geographic disparities in factual recall, emphasizing the need for more balanced global representation in LLM training. We also observe a Pearson correlation of more than 0.7 between models' performance in TiEBe and various countries' socioeconomic indicators, such as HDI. In addition, we examine the impact of language on factual recall by posing questions in the native language of the region where each event occurred, uncovering substantial performance gaps for low-resource languages.
