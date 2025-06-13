---
layout: publication
title: 'DATETIME: A New Benchmark To Measure LLM Translation And Reasoning Capabilities'
authors: Edward Gaere, Florian Wangenheim
conference: "Arxiv"
year: 2025
bibkey: gaere2025new
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16155"}
tags: ['GPT', 'Model Architecture']
---
This paper introduces DATETIME, a new high-quality benchmark designed to
evaluate the translation and reasoning abilities of a Large Language Model
(LLM) on datetimes. A datetime is simply a date and a time, for example
'11th.february.2023 ,1:12:31'. Datetimes are an interesting domain because they
are intuitive and straightforward for humans to process but present significant
challenges for LLMs. At the time of writing, no publicly available benchmark
exists for systematically evaluating LLMs on datetime processing. Our
experiments show that state-of-the-art models exhibit significant difficulty
with tasks involving reasoning on datetimes, and that General Artificial
Intelligence is still a distant aspiration. We hypothesize that working with
datetimes necessitates translation and/or computation capabilities, and the
tasks of the benchmark are organized accordingly. Significant dispersion in
performance across models is observed with surprisingly poor performance even
on apparently trivial tasks. Whilst frontier models such as ChatGPT, Claude and
Llama3.1 have evidently been built and trained with datetime reasoning
abilities, significant improvement is required for the open-source models.
