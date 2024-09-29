---
layout: publication
title: Limits Of Transformer Language Models On Learning To Compose Algorithms
authors: Thomm Jonathan, Terzic Aleksandar, Camposampiero Giacomo, Hersche Michael, Schölkopf Bernhard, Rahimi Abbas
conference: "Arxiv"
year: 2024
bibkey: thomm2024limits
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05785"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We analyze the capabilities of Transformer language models in learning compositional discrete tasks. To this end we evaluate training LLaMA models and prompting GPT45;4 and Gemini on four tasks demanding to learn a composition of several discrete sub45;tasks. On both training LLaMA models from scratch and prompting on GPT45;4 and Gemini we measure how well these models can reuse primitives observable in the sub45;tasks to learn the composition task. Our results indicate that compositional learning in state45;of45;the45;art Transformer language models is highly sample inefficient LLaMA requires more data samples than relearning all sub45;tasks from scratch to learn the compositional task; in45;context prompting with few samples is unreliable and fails at executing the sub45;tasks or correcting the errors in multi45;round code generation. Further by leveraging complexity theory we support these findings with a theoretical analysis focused on the sample inefficiency of gradient descent in memorizing feedforward models.
