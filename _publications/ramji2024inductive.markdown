---
layout: publication
title: 'Inductive Linguistic Reasoning With Large Language Models'
authors: Raghav Ramji, Keshav Ramji
conference: "Arxiv"
year: 2024
bibkey: ramji2024inductive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.17819'}
tags: ['Prompting', 'GPT', 'Model Architecture']
---
Evaluating large language models (LLMs) on their linguistic reasoning
capabilities is an important task to understand the gaps in their skills that
may surface during large-scale adoption. In this work, we investigate the
abilities of such models to perform abstract multilingual reasoning through the
lens of linguistic puzzles on extremely low-resource languages. As these
translation tasks involve inductive and deductive reasoning from reference
instances, we examine whether diverse auxiliary demonstrations can be
automatically induced from seed exemplars, through analogical prompting. We
employ a two-stage procedure, first generating analogical exemplars with a
language model, and then applying them in-context along with provided target
language exemplars. Our results on the modeLing dataset show that analogical
prompting is effective in eliciting models' knowledge of language grammar
similarities, boosting the performance of GPT-4o by as much as 8.1% and
Llama-3.1-405B-Instruct by 5.9% over chain-of-thought approaches. These gains
are attributable to the analogical demonstrations, both when self-generated as
well as when produced by weaker multilingual models. Furthermore, we
demonstrate that our method generalizes to other tasks present in Linguistics
Olympiad competitions, achieving sizable improvements across all problem types
and difficulty levels included in the LINGOLY dataset with GPT-4o. We also
report several findings about interesting phenomena which drive linguistic
reasoning performance, suggesting that such puzzles are a valuable benchmark
for new reasoning methods.
