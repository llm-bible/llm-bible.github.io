---
layout: publication
title: 'Winodict: Probing Language Models For In-context Word Acquisition'
authors: Julian Martin Eisenschlos, Jeremy R. Cole, Fangyu Liu, William W. Cohen
conference: "Arxiv"
year: 2022
bibkey: eisenschlos2022probing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2209.12153'}
tags: ['Prompting', 'In-Context Learning']
---
We introduce a new in-context learning paradigm to measure Large Language
Models' (LLMs) ability to learn novel words during inference. In particular, we
rewrite Winograd-style co-reference resolution problems by replacing the key
concept word with a synthetic but plausible word that the model must understand
to complete the task. Solving this task requires the model to make use of the
dictionary definition of the new word given in the prompt. This benchmark
addresses word acquisition, one important aspect of the diachronic degradation
known to afflict LLMs. As LLMs are frozen in time at the moment they are
trained, they are normally unable to reflect the way language changes over
time. We show that the accuracy of LLMs compared to the original Winograd tasks
decreases radically in our benchmark, thus identifying a limitation of current
models and providing a benchmark to measure future improvements in LLMs ability
to do in-context learning.
