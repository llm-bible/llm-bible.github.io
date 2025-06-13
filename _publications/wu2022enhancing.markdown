---
layout: publication
title: 'Enhancing Pre-trained Models With Text Structure Knowledge For Question Generation'
authors: Zichen Key Laboratory Of Computational Linguistics, Ministry Of Education, China, School Of Computer Science, Peking University, China Wu, Xin Key Laboratory Of Computational Linguistics, Ministry Of Education, China, School Of Computer Science, Peking University, China Jia, Fanyi Key Laboratory Of Computational Linguistics, Ministry Of Education, China, School Of Computer Science, Peking University, China Qu, Yunfang Key Laboratory Of Computational Linguistics, Ministry Of Education, China, School Of Computer Science, Peking University, China Wu
conference: "Arxiv"
year: 2022
bibkey: wu2022enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2209.04179'}
tags: ['Attention Mechanism', 'Ethics and Bias', 'Transformer', 'Model Architecture']
---
Today the pre-trained language models achieve great success for question
generation (QG) task and significantly outperform traditional
sequence-to-sequence approaches. However, the pre-trained models treat the
input passage as a flat sequence and are thus not aware of the text structure
of input passage. For QG task, we model text structure as answer position and
syntactic dependency, and propose answer localness modeling and syntactic mask
attention to address these limitations. Specially, we present localness
modeling with a Gaussian bias to enable the model to focus on answer-surrounded
context, and propose a mask attention mechanism to make the syntactic structure
of input passage accessible in question generation process. Experiments on
SQuAD dataset show that our proposed two modules improve performance over the
strong pre-trained model ProphetNet, and combing them together achieves very
competitive results with the state-of-the-art pre-trained model.
