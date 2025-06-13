---
layout: publication
title: 'Language Models Fail To Introspect About Their Knowledge Of Language'
authors: Siyuan Song, Jennifer Hu, Kyle Mahowald
conference: "Arxiv"
year: 2025
bibkey: song2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07513"}
tags: ['Prompting', 'Reinforcement Learning']
---
There has been recent interest in whether large language models (LLMs) can
introspect about their own internal states. Such abilities would make LLMs more
interpretable, and also validate the use of standard introspective methods in
linguistics to evaluate grammatical knowledge in models (e.g., asking "Is this
sentence grammatical?"). We systematically investigate emergent introspection
across 21 open-source LLMs, in two domains where introspection is of
theoretical interest: grammatical knowledge and word prediction. Crucially, in
both domains, a model's internal linguistic knowledge can be theoretically
grounded in direct measurements of string probability. We then evaluate whether
models' responses to metalinguistic prompts faithfully reflect their internal
knowledge. We propose a new measure of introspection: the degree to which a
model's prompted responses predict its own string probabilities, beyond what
would be predicted by another model with nearly identical internal knowledge.
While both metalinguistic prompting and probability comparisons lead to high
task accuracy, we do not find evidence that LLMs have privileged "self-access".
Our findings complicate recent results suggesting that models can introspect,
and add new evidence to the argument that prompted responses should not be
conflated with models' linguistic generalizations.
