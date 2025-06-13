---
layout: publication
title: 'Output Scouting: Auditing Large Language Models For Catastrophic Responses'
authors: Andrew Bell, Joao Fonseca
conference: "Arxiv"
year: 2024
bibkey: bell2024output
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05305'}
  - {name: "Code", url: 'https://github.com/joaopfonseca/outputscouting)'}
tags: ['Has Code', 'Transformer', 'Model Architecture', 'Tools', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
Recent high profile incidents in which the use of Large Language Models
(LLMs) resulted in significant harm to individuals have brought about a growing
interest in AI safety. One reason LLM safety issues occur is that models often
have at least some non-zero probability of producing harmful outputs. In this
work, we explore the following scenario: imagine an AI safety auditor is
searching for catastrophic responses from an LLM (e.g. a "yes" responses to
"can I fire an employee for being pregnant?"), and is able to query the model a
limited number times (e.g. 1000 times). What is a strategy for querying the
model that would efficiently find those failure responses? To this end, we
propose output scouting: an approach that aims to generate semantically fluent
outputs to a given prompt matching any target probability distribution. We then
run experiments using two LLMs and find numerous examples of catastrophic
responses. We conclude with a discussion that includes advice for practitioners
who are looking to implement LLM auditing for catastrophic responses. We also
release an open-source toolkit (https://github.com/joaopfonseca/outputscouting)
that implements our auditing framework using the Hugging Face transformers
library.
