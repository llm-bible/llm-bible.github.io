---
layout: publication
title: Imagination Is All You Need! Curved Contrastive Learning For Abstract Sequence Modeling Utilized On Long Short45;term Dialogue Planning
authors: Erker Justus-jonas, Schaffer Stefan, Spanakis Gerasimos
conference: "Arxiv"
year: 2022
bibkey: erker2022imagination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.07591"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Inspired by the curvature of space45;time (Einstein 1921) we introduce Curved Contrastive Learning (CCL) a novel representation learning technique for learning the relative turn distance between utterance pairs in multi45;turn dialogues. The resulting bi45;encoder models can guide transformers as a response ranking model towards a goal in a zero45;shot fashion by projecting the goal utterance and the corresponding reply candidates into a latent space. Here the cosine similarity indicates the distance/reachability of a candidate utterance toward the corresponding goal. Furthermore we explore how these forward45;entailing language representations can be utilized for assessing the likelihood of sequences by the entailment strength i.e. through the cosine similarity of its individual members (encoded separately) as an emergent property in the curved space. These non45;local properties allow us to imagine the likelihood of future patterns in dialogues specifically by ordering/identifying future goal utterances that are multiple turns away given a dialogue context. As part of our analysis we investigate characteristics that make conversations (un)plannable and find strong evidence of planning capability over multiple turns (in 61.5637; over 3 turns) in conversations from the DailyDialog (Li et al. 2017) dataset. Finally we show how we achieve higher efficiency in sequence modeling tasks compared to previous work thanks to our relativistic approach where only the last utterance needs to be encoded and computed during inference.
