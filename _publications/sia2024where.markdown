---
layout: publication
title: Where Does In45;context Translation Happen In Large Language Models
authors: Sia Suzanna, Mueller David, Duh Kevin
conference: "Arxiv"
year: 2024
bibkey: sia2024where
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04510"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Prompting']
---
Self45;supervised large language models have demonstrated the ability to perform Machine Translation (MT) via in45;context learning but little is known about where the model performs the task with respect to prompt instructions and demonstration examples. In this work we attempt to characterize the region where large language models transition from in45;context learners to translation models. Through a series of layer45;wise context45;masking experiments on textsc123;GPTNeo2.7B125; textsc123;Bloom3B125; textsc123;Llama7b125; and textsc123;Llama7b45;chat125; we demonstrate evidence of a task recognition point where the translation task is encoded into the input representations and attention to context is no longer necessary. We further observe correspondence between the low performance when masking out entire layers and the task recognition layers. Taking advantage of this redundancy results in 4537; computational savings when prompting with 5 examples and task recognition achieved at layer 14 / 32. Our layer45;wise fine45;tuning experiments indicate that the most effective layers for MT fine45;tuning are the layers critical to task recognition.
