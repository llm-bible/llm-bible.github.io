---
layout: publication
title: 'A Case Study Of Web App Coding With Openai Reasoning Models'
authors: Yi Cui
conference: "Arxiv"
year: 2024
bibkey: cui2024case
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.13773'}
tags: ['Fine-Tuning']
---
This paper presents a case study of coding tasks by the latest reasoning
models of OpenAI, i.e. o1-preview and o1-mini, in comparison with other
frontier models. The o1 models deliver SOTA results for WebApp1K, a single-task
benchmark. To this end, we introduce WebApp1K-Duo, a harder benchmark doubling
number of tasks and test cases. The new benchmark causes the o1 model
performances to decline significantly, falling behind Claude 3.5. Moreover,
they consistently fail when confronted with atypical yet correct test cases, a
trap non-reasoning models occasionally avoid. We hypothesize that the
performance variability is due to instruction comprehension. Specifically, the
reasoning mechanism boosts performance when all expectations are captured,
meanwhile exacerbates errors when key expectations are missed, potentially
impacted by input lengths. As such, we argue that the coding success of
reasoning models hinges on the top-notch base model and SFT to ensure
meticulous adherence to instructions.
