---
layout: publication
title: 'Discovering Useful Sentence Representations From Large Pretrained Language Models'
authors: Subramani Nishant, Suresh Nivedita
conference: "Arxiv"
year: 2020
bibkey: subramani2020discovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.09049"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Despite the extensive success of pretrained language models as encoders for building NLP systems, they haven't seen prominence as decoders for sequence generation tasks. We explore the question of whether these models can be adapted to be used as universal decoders. To be considered universal, a decoder must have an implicit representation for any target sentence \(s\), such that it can recover that sentence exactly when conditioned on its representation. For large transformer-based language models trained on vast amounts of English text, we investigate whether such representations can be easily discovered using standard optimization methods. We present and compare three representation injection techniques for transformer-based models and three accompanying methods which map sentences to and from this representation space. Experiments show that not only do representations exist for sentences from a variety of genres. More importantly, without needing complex optimization algorithms, our methods recover these sentences almost perfectly without fine-tuning the underlying language model at all.
