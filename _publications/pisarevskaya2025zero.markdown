---
layout: publication
title: 'Zero-shot And Few-shot Learning With Instruction-following Llms For Claim Matching In Automated Fact-checking'
authors: Dina Pisarevskaya, Arkaitz Zubiaga
conference: "Proceedings of the 31st International Conference on Computational Linguistics 2025 pages 9721-9736 Abu Dhabi UAE"
year: 2025
bibkey: pisarevskaya2025zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.10860"}
tags: ['GPT', 'RAG', 'Model Architecture', 'Few-Shot', 'Prompting']
---
The claim matching (CM) task can benefit an automated fact-checking pipeline
by putting together claims that can be resolved with the same fact-check. In
this work, we are the first to explore zero-shot and few-shot learning
approaches to the task. We consider CM as a binary classification task and
experiment with a set of instruction-following large language models
(GPT-3.5-turbo, Gemini-1.5-flash, Mistral-7B-Instruct, and
Llama-3-8B-Instruct), investigating prompt templates. We introduce a new CM
dataset, ClaimMatch, which will be released upon acceptance. We put LLMs to the
test in the CM task and find that it can be tackled by leveraging more mature
yet similar tasks such as natural language inference or paraphrase detection.
We also propose a pipeline for CM, which we evaluate on texts of different
lengths.
