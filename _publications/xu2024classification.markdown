---
layout: publication
title: 'Llms'' Classification Performance Is Overclaimed'
authors: Hanzi Xu, Renze Lou, Jiangshu Du, Vahid Mahzoon, Elmira Talebianaraki, Zhuoan Zhou, Elizabeth Garrison, Slobodan Vucetic, Wenpeng Yin
conference: "Arxiv"
year: 2024
bibkey: xu2024classification
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.16203'}
tags: ['Reinforcement Learning']
---
In many classification tasks designed for AI or human to solve, gold labels
are typically included within the label space by default, often posed as "which
of the following is correct?" This standard setup has traditionally highlighted
the strong performance of advanced AI, particularly top-performing Large
Language Models (LLMs), in routine classification tasks. However, when the gold
label is intentionally excluded from the label space, it becomes evident that
LLMs still attempt to select from the available label candidates, even when
none are correct. This raises a pivotal question: Do LLMs truly demonstrate
their intelligence in understanding the essence of classification tasks?
  In this study, we evaluate both closed-source and open-source LLMs across
representative classification tasks, arguing that the perceived performance of
LLMs is overstated due to their inability to exhibit the expected comprehension
of the task. This paper makes a threefold contribution: i) To our knowledge,
this is the first work to identify the limitations of LLMs in classification
tasks when gold labels are absent. We define this task as Classify-w/o-Gold and
propose it as a new testbed for LLMs. ii) We introduce a benchmark, Know-No,
comprising two existing classification tasks and one new task, to evaluate
Classify-w/o-Gold. iii) This work defines and advocates for a new evaluation
metric, OmniAccuracy, which assesses LLMs' performance in classification tasks
both when gold labels are present and absent.
