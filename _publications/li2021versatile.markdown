---
layout: publication
title: 'VUT: Versatile UI Transformer For Multi-modal Multi-task User Interface Modeling'
authors: Yang Li, Gang Li, Xin Zhou, Mostafa Dehghani, Alexey Gritsenko
conference: "Arxiv"
year: 2021
bibkey: li2021versatile
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2112.05692'}
tags: ['Multimodal Models', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
User interface modeling is inherently multimodal, which involves several
distinct types of data: images, structures and language. The tasks are also
diverse, including object detection, language generation and grounding. In this
paper, we present VUT, a Versatile UI Transformer that takes multimodal input
and simultaneously accomplishes 5 distinct tasks with the same model. Our model
consists of a multimodal Transformer encoder that jointly encodes UI images and
structures, and performs UI object detection when the UI structures are absent
in the input. Our model also consists of an auto-regressive Transformer model
that encodes the language input and decodes output, for both question-answering
and command grounding with respect to the UI. Our experiments show that for
most of the tasks, when trained jointly for multi-tasks, VUT substantially
reduces the number of models and footprints needed for performing multiple
tasks, while achieving accuracy exceeding or on par with baseline models
trained for each individual task.
