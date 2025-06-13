---
layout: publication
title: 'Making Large Language Models Better Reasoners With Orchestrated Streaming Experiences'
authors: Xiangyang Liu, Junliang He, Xipeng Qiu
conference: "Arxiv"
year: 2025
bibkey: liu2025making
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00473'}
tags: ['Few-Shot', 'Model Architecture', 'Tools', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) can perform complex reasoning by generating
intermediate thoughts under zero-shot or few-shot settings. However, zero-shot
prompting always encounters low performance, and the superior performance of
few-shot prompting hinges on the manual-crafted demonstrations. In this paper,
we present RoSE (Reasoning with Orchestrated Streaming Experiences), a general
framework for solving reasoning tasks that can self-improve without complex
external efforts. To enable RoSE, we describe an architecture that extends an
LLM to store all answered questions and their thoughts in a streaming
experience pool then orchestrates helpful questions from the pool to assist in
answering new questions. To set up a question-aware orchestration mechanism,
RoSE first calculates the similarity of each question in the pool with a new
test question. Since the solution to each answered question is not always
correct, RoSE will sort the questions according to their similarity with the
new question, and then uniformly divide them into multiple buckets. It finally
extracts one question from each bucket to make these extracted questions more
diverse. To make these extracted questions help RoSE answer new questions as
much as possible, we introduce two other attributes of uncertainty and
complexity for each question. RoSE will preferentially select the questions
with low uncertainty and high complexity from each bucket. We evaluate the
versatility of RoSE in various reasoning tasks, LLMs, and CoT methods.
