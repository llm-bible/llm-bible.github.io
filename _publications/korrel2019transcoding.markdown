---
layout: publication
title: 'Transcoding Compositionally: Using Attention To Find More Generalizable Solutions'
authors: Korrel Kris, Hupkes Dieuwke, Dankers Verna, Bruni Elia
conference: "Arxiv"
year: 2019
bibkey: korrel2019transcoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1906.01234"}
tags: ['Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Uncategorized']
---
While sequence-to-sequence models have shown remarkable generalization power across several natural language tasks, their construct of solutions are argued to be less compositional than human-like generalization. In this paper, we present seq2attn, a new architecture that is specifically designed to exploit attention to find compositional patterns in the input. In seq2attn, the two standard components of an encoder-decoder model are connected via a transcoder, that modulates the information flow between them. We show that seq2attn can successfully generalize, without requiring any additional supervision, on two tasks which are specifically constructed to challenge the compositional skills of neural networks. The solutions found by the model are highly interpretable, allowing easy analysis of both the types of solutions that are found and potential causes for mistakes. We exploit this opportunity to introduce a new paradigm to test compositionality that studies the extent to which a model overgeneralizes when confronted with exceptions. We show that seq2attn exhibits such overgeneralization to a larger degree than a standard sequence-to-sequence model.
