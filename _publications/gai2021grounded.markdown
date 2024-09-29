---
layout: publication
title: Grounded Graph Decoding Improves Compositional Generalization in Question Answering
authors: Gai Yu, Jain Paras, Zhang Wendi, Gonzalez Joseph E., Song Dawn, Stoica Ion
conference: "Arxiv"
year: 2021
bibkey: gai2021grounded
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.03642"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques', 'Transformer']
---
Question answering models struggle to generalize to novel compositions of training patterns such to longer sequences or more complex test structures. Current end-to-end models learn a flat input embedding which can lose input syntax context. Prior approaches improve generalization by learning permutation invariant models but these methods do not scale to more complex train-test splits. We propose Grounded Graph Decoding a method to improve compositional generalization of language representations by grounding structured predictions with an attention mechanism. Grounding enables the model to retain syntax information from the input in thereby significantly improving generalization over complex inputs. By predicting a structured graph containing conjunctions of query clauses we learn a group invariant representation without making assumptions on the target domain. Our model significantly outperforms state-of-the-art baselines on the Compositional Freebase Questions (CFQ) dataset a challenging benchmark for compositional generalization in question answering. Moreover we effectively solve the MCD1 split with 98 accuracy.
