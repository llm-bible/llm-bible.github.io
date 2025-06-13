---
layout: publication
title: 'Uncovering Differences In Persuasive Language In Russian Versus English Wikipedia'
authors: Bryan Li, Aleksey Panasyuk, Chris Callison-burch
conference: "Arxiv"
year: 2024
bibkey: li2024uncovering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.19148'}
tags: ['Prompting']
---
We study how differences in persuasive language across Wikipedia articles,
written in either English and Russian, can uncover each culture's distinct
perspective on different subjects. We develop a large language model (LLM)
powered system to identify instances of persuasive language in multilingual
texts. Instead of directly prompting LLMs to detect persuasion, which is
subjective and difficult, we propose to reframe the task to instead ask
high-level questions (HLQs) which capture different persuasive aspects.
Importantly, these HLQs are authored by LLMs themselves. LLMs over-generate a
large set of HLQs, which are subsequently filtered to a small set aligned with
human labels for the original task. We then apply our approach to a
large-scale, bilingual dataset of Wikipedia articles (88K total), using a
two-stage identify-then-extract prompting strategy to find instances of
persuasion.
  We quantify the amount of persuasion per article, and explore the differences
in persuasion through several experiments on the paired articles. Notably, we
generate rankings of articles by persuasion in both languages. These rankings
match our intuitions on the culturally-salient subjects; Russian Wikipedia
highlights subjects on Ukraine, while English Wikipedia highlights the Middle
East. Grouping subjects into larger topics, we find politically-related events
contain more persuasion than others. We further demonstrate that HLQs obtain
similar performance when posed in either English or Russian. Our methodology
enables cross-lingual, cross-cultural understanding at scale, and we release
our code, prompts, and data.
