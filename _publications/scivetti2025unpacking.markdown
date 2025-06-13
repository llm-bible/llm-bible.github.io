---
layout: publication
title: 'Unpacking Let Alone: Human-scale Models Generalize To A Rare Construction In Form But Not Meaning'
authors: Wesley Scivetti, Tatsuya Aoyama, Ethan Wilcox, Nathan Schneider
conference: "Arxiv"
year: 2025
bibkey: scivetti2025unpacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04408"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Humans have a remarkable ability to acquire and understand grammatical phenomena that are seen rarely, if ever, during childhood. Recent evidence suggests that language models with human-scale pretraining data may possess a similar ability by generalizing from frequent to rare constructions. However, it remains an open question how widespread this generalization ability is, and to what extent this knowledge extends to meanings of rare constructions, as opposed to just their forms. We fill this gap by testing human-scale transformer language models on their knowledge of both the form and meaning of the (rare and quirky) English LET-ALONE construction. To evaluate our LMs we construct a bespoke synthetic benchmark that targets syntactic and semantic properties of the construction. We find that human-scale LMs are sensitive to form, even when related constructions are filtered from the dataset. However, human-scale LMs do not make correct generalizations about LET-ALONE's meaning. These results point to an asymmetry in the current architectures' sample efficiency between language form and meaning, something which is not present in human language learners.
