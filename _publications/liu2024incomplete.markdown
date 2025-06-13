---
layout: publication
title: 'An Incomplete Loop: Instruction Inference, Instruction Following, And In-context Learning In Language Models'
authors: Emmy Liu, Graham Neubig, Jacob Andreas
conference: "Arxiv"
year: 2024
bibkey: liu2024incomplete
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03028"}
tags: ['Model Architecture', 'Few-Shot', 'GPT', 'Prompting', 'Applications', 'In-Context Learning']
---
Modern language models (LMs) can learn to perform new tasks in different
ways: in instruction following, the target task is described explicitly in
natural language; in few-shot prompting, the task is specified implicitly with
a small number of examples; in instruction inference, LMs are presented with
in-context examples and are then prompted to generate a natural language task
description before making predictions. Each of these procedures may be thought
of as invoking a different form of reasoning: instruction following involves
deductive reasoning, few-shot prompting involves inductive reasoning, and
instruction inference involves abductive reasoning. How do these different
capabilities relate? Across four LMs (from the gpt and llama families) and two
learning problems (involving arithmetic functions and machine translation) we
find a strong dissociation between the different types of reasoning: LMs can
sometimes learn effectively from few-shot prompts even when they are unable to
explain their own prediction rules; conversely, they sometimes infer useful
task descriptions while completely failing to learn from human-generated
descriptions of the same task. Our results highlight the non-systematic nature
of reasoning even in some of today's largest LMs, and underscore the fact that
very different learning mechanisms may be invoked by seemingly similar
prompting procedures.
