---
layout: publication
title: 'Task Prompt Vectors: Effective Initialization Through Multi-task Soft-prompt Transfer'
authors: Robert Belanec, Simon Ostermann, Ivan Srba, Maria Bielikova
conference: "Arxiv"
year: 2024
bibkey: belanec2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01119"}
tags: ['Prompting', 'Training Techniques', 'Model Architecture']
---
Prompt tuning is an efficient solution for training large language models
(LLMs). However, current soft-prompt-based methods often sacrifice multi-task
modularity, requiring the training process to be fully or partially repeated
for each newly added task. While recent work on task vectors applied arithmetic
operations on full model weights to achieve the desired multi-task performance,
a similar approach for soft-prompts is still missing. To this end, we introduce
Task Prompt Vectors, created by element-wise difference between weights of
tuned soft-prompts and their random initialization. Experimental results on 12
NLU datasets show that task prompt vectors can be used in low-resource settings
to effectively initialize prompt tuning on similar tasks. In addition, we show
that task prompt vectors are independent of the random initialization of prompt
tuning on 2 different language model architectures. This allows prompt
arithmetics with the pre-trained vectors from different tasks. In this way, we
provide a competitive alternative to state-of-the-art baselines by arithmetic
addition of task prompt vectors from multiple tasks.
