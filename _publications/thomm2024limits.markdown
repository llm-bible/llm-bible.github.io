---
layout: publication
title: 'Limits Of Transformer Language Models On Learning To Compose Algorithms'
authors: Jonathan Thomm, Giacomo Camposampiero, Aleksandar Terzic, Michael Hersche, Bernhard Schölkopf, Abbas Rahimi
conference: "Arxiv"
year: 2024
bibkey: thomm2024limits
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05785"}
  - {name: "Code", url: "https://github.com/IBM/limitations-lm-algorithmic-compositional-learning"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
We analyze the capabilities of Transformer language models in learning
compositional discrete tasks. To this end, we evaluate training LLaMA models
and prompting GPT-4 and Gemini on four tasks demanding to learn a composition
of several discrete sub-tasks. In particular, we measure how well these models
can reuse primitives observable in the sub-tasks to learn the composition task.
Our results indicate that compositional learning in state-of-the-art
Transformer language models is highly sample inefficient: LLaMA requires more
data samples than relearning all sub-tasks from scratch to learn the
compositional task; in-context prompting with few samples is unreliable and
fails at executing the sub-tasks or correcting the errors in multi-round code
generation. Further, by leveraging complexity theory, we support these findings
with a theoretical analysis focused on the sample inefficiency of gradient
descent in memorizing feedforward models. We open source our code at
https://github.com/IBM/limitations-lm-algorithmic-compositional-learning.
