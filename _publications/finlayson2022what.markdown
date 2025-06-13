---
layout: publication
title: 'What Makes Instruction Learning Hard? An Investigation And A New Challenge In A Synthetic Environment'
authors: Matthew Finlayson, Kyle Richardson, Ashish Sabharwal, Peter Clark
conference: "Arxiv"
year: 2022
bibkey: finlayson2022what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.09148"}
tags: ['Fine-Tuning', 'Transformer', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
The instruction learning paradigm -- where a model learns to perform new
tasks from task descriptions alone -- has become popular in general-purpose
model research. The capabilities of large transformer models as instruction
learners, however, remain poorly understood. We use a controlled synthetic
environment to characterize such capabilities. Specifically, we use the task of
deciding whether a given string matches a regular expression (viewed as an
instruction) to identify properties of tasks, instructions, and instances that
make instruction learning challenging. For instance, we find that our model, a
fine-tuned T5-based text2text transformer, struggles with large regular
languages, suggesting that less precise instructions are challenging for
models. Additionally, instruction executions that require tracking longer
contexts of prior steps are also more difficult. We use our findings to
systematically construct a challenging instruction learning dataset, which we
call Hard RegSet. Fine-tuning on Hard RegSet, our large transformer learns to
correctly interpret only 65.6% of test instructions (with at least 90%
accuracy), and 11%-24% of the instructions in out-of-distribution
generalization settings. We propose Hard RegSet as a challenging instruction
learning task, and a controlled environment for studying instruction learning.
