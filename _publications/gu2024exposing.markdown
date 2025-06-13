---
layout: publication
title: 'Simpletom: Exposing The Gap Between Explicit Tom Inference And Implicit Tom Application In Llms'
authors: Yuling Gu, Oyvind Tafjord, Hyunwoo Kim, Jared Moore, Ronan Le Bras, Peter Clark, Yejin Choi
conference: "Arxiv"
year: 2024
bibkey: gu2024exposing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13648"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Reinforcement Learning']
---
While prior work has explored whether large language models (LLMs) possess a
"theory of mind" (ToM) - the ability to attribute mental states to oneself and
others - there has been little work testing whether LLMs can implicitly apply
such knowledge to predict behavior, or to judge whether an observed behavior is
rational. Such skills are critical for appropriate interaction in social
environments. We create a new dataset, SimpleTom, containing concise, diverse
stories (e.g., "The can of Pringles has moldy chips in it. Mary picks up the
can in the supermarket and walks to the cashier."), each with three questions
that test different degrees of ToM reasoning, asking models to predict (a)
mental state ("Is Mary aware of the mold?"), (b) behavior ("Will Mary pay for
the chips or report the mold?"), and (c) judgment ("Mary paid for the chips.
Was that reasonable?"). To our knowledge, SimpleToM is the first dataset to
systematically explore downstream reasoning requiring knowledge of mental
states in realistic scenarios. Our experimental results are intriguing: While
most models can reliably predict mental state on our dataset (a), they often
fail to correctly predict the behavior (b), and fare even worse at judging
whether given behaviors are reasonable (c), despite being correctly aware of
the protagonist's mental state should make such secondary predictions obvious.
We further show that we can help models do better at (b) and (c) via
interventions such as reminding the model of its earlier mental state answer
and mental-state-specific chain-of-thought prompting, raising the action
prediction accuracies (e.g., from 49.5% to 93.5% for GPT-4o) and judgment
accuracies (e.g., from 15.3% to 94.7% in GPT-4o). While this shows that models
can be coaxed to perform well, it requires task-specific interventions, and the
natural model performances remain low, a cautionary tale for LLM deployment.
