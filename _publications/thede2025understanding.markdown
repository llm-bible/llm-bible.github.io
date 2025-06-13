---
layout: publication
title: 'Understanding The Limits Of Lifelong Knowledge Editing In Llms'
authors: Lukas Thede, Karsten Roth, Matthias Bethge, Zeynep Akata, Tom Hartvigsen
conference: "Arxiv"
year: 2025
bibkey: thede2025understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05683"}
tags: ['Training Techniques', 'Reinforcement Learning']
---
Keeping large language models factually up-to-date is crucial for deployment,
yet costly retraining remains a challenge. Knowledge editing offers a promising
alternative, but methods are only tested on small-scale or synthetic edit
benchmarks. In this work, we aim to bridge research into lifelong knowledge
editing to real-world edits at practically relevant scale. We first introduce
WikiBigEdit; a large-scale benchmark of real-world Wikidata edits, built to
automatically extend lifelong for future-proof benchmarking. In its first
instance, it includes over 500K question-answer pairs for knowledge editing
alongside a comprehensive evaluation pipeline. Finally, we use WikiBigEdit to
study existing knowledge editing techniques' ability to incorporate large
volumes of real-world facts and contrast their capabilities to generic
modification techniques such as retrieval augmentation and continual finetuning
to acquire a complete picture of the practical extent of current lifelong
knowledge editing.
