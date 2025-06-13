---
layout: publication
title: 'One Ruler To Measure Them All: Benchmarking Multilingual Long-context Language Models'
authors: Yekyung Kim, Jenna Russell, Marzena Karpinska, Mohit Iyyer
conference: "Arxiv"
year: 2025
bibkey: kim2025one
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01996'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Merging']
---
We present ONERULER, a multilingual benchmark designed to evaluate
long-context language models across 26 languages. ONERULER adapts the
English-only RULER benchmark (Hsieh et al., 2024) by including seven synthetic
tasks that test both retrieval and aggregation, including new variations of the
"needle-in-a-haystack" task that allow for the possibility of a nonexistent
needle. We create ONERULER through a two-step process, first writing English
instructions for each task and then collaborating with native speakers to
translate them into 25 additional languages. Experiments with both open-weight
and closed LLMs reveal a widening performance gap between low- and
high-resource languages as context length increases from 8K to 128K tokens.
Surprisingly, English is not the top-performing language on long-context tasks
(ranked 6th out of 26), with Polish emerging as the top language. Our
experiments also show that many LLMs (particularly OpenAI's o3-mini-high)
incorrectly predict the absence of an answer, even in high-resource languages.
Finally, in cross-lingual scenarios where instructions and context appear in
different languages, performance can fluctuate by up to 20% depending on the
instruction language. We hope the release of ONERULER will facilitate future
research into improving multilingual and cross-lingual long-context training
pipelines.
