---
layout: publication
title: 'The Unreasonable Effectiveness Of Eccentric Automatic Prompts'
authors: Rick Battle, Teja Gollapudi
conference: "Arxiv"
year: 2024
bibkey: battle2024unreasonable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.10949'}
tags: ['Prompting', 'Efficiency and Optimization']
---
Large Language Models (LLMs) have demonstrated remarkable problem-solving and
basic mathematics abilities. However, their efficacy is highly contingent on
the formulation of the prompt. This study endeavors to quantify the influence
of incorporating "positive thinking" into the system message of the prompt,
then compare that to systematic prompt optimization. We assess the performance
of 60 combinations of system message snippets, tested with and without Chain of
Thought prompting, across three models with parameters ranging from 7 to 70
billion on the GSM8K dataset. Our findings reveal that results do not
universally generalize across models. In most instances, the inclusion of
"positive thinking" prompts positively affected model performance. Notably,
however, Llama2-70B exhibited an exception when not utilizing Chain of Thought,
as the optimal system message was found to be none at all. Given the
combinatorial complexity, and thus computation time, of experimenting with
hand-tuning prompts for large black-box models, we then compared the
performance of the best "positive thinking" prompt against the output of
systematic prompt optimization. We show that employing an automated prompt
optimizer emerges as the most effective method for enhancing performance, even
when working with smaller open-source models. Additionally, our findings reveal
that the highest-scoring, automatically-optimized prompt exhibits a degree of
peculiarity far beyond expectations.
