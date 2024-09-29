---
layout: publication
title: Where does In-context Translation Happen in Large Language Models
authors: Sia Suzanna, Mueller David, Duh Kevin
conference: "Arxiv"
year: 2024
bibkey: sia2024where
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04510"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Self-supervised large language models have demonstrated the ability to perform Machine Translation (MT) via in-context learning but little is known about where the model performs the task with respect to prompt instructions and demonstration examples. In this work we attempt to characterize the region where large language models transition from in-context learners to translation models. Through a series of layer-wise context-masking experiments on and we demonstrate evidence of a task recognition point where the translation task is encoded into the input representations and attention to context is no longer necessary. We further observe correspondence between the low performance when masking out entire layers and the task recognition layers. Taking advantage of this redundancy results in 45 computational savings when prompting with 5 examples and task recognition achieved at layer 14 / 32. Our layer-wise fine-tuning experiments indicate that the most effective layers for MT fine-tuning are the layers critical to task recognition.
