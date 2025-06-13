---
layout: publication
title: 'Certified Deductive Reasoning With Language Models'
authors: Gabriel Poesia, Kanishk Gandhi, Eric Zelikman, Noah D. Goodman
conference: "Arxiv"
year: 2023
bibkey: poesia2023certified
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.04031'}
tags: ['GPT', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Language models often achieve higher accuracy when reasoning step-by-step in
complex tasks. However, even when arriving at a correct final answer, their
rationales are often logically unsound or inconsistent. This is a major issue
when reliable reasoning traces are needed, such when fine-tuning on
model-generated reasoning for self-improvement. To tackle these issues, we
introduce a class of tools for language models called *guides*, that use
state and incremental constraints to guide generation. A guide can be invoked
by the model to constrain its own generation to a set of valid statements given
by the tool. In turn, the model's choices can change the guide's state. We show
how a general system for logical reasoning can be used as a guide, which we
call \textsc\{LogicGuide\}. Given a reasoning problem in natural language, a
model can formalize its assumptions for \textsc\{LogicGuide\} and guarantee that
its step-by-step reasoning is sound. In experiments on PrOntoQA, ProofWriter
and Syllogism Validity datasets, \textsc\{LogicGuide\} significantly improves the
performance of GPT-3, GPT-3.5 Turbo and LLaMA (accuracy gains up to 35%),
while drastically reducing *content effects* -- the interference between
unwanted prior assumptions and reasoning, which humans and language models
suffer from. We then explore bootstrapping GPT-3.5 Turbo and LLaMA using their
own reasoning traces. We find that LogicGuide is critical: by training only on
certified self-generated reasoning, models can self-improve, avoiding learning
from their own hallucinations. Moreover, bootstrapped models enjoy significant
boosts on ReClor, a challenging real-world reasoning dataset, even when not
relying on formalization at inference time.
