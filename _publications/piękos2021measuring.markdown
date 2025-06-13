---
layout: publication
title: 'Measuring And Improving Bert''s Mathematical Abilities By Predicting The Order Of Reasoning'
authors: Piotr Piękos, Henryk Michalewski, Mateusz Malinowski
conference: "Arxiv"
year: 2021
bibkey: piękos2021measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.03921"}
tags: ['Training Techniques', 'Ethics and Bias', 'BERT', 'Model Architecture']
---
Imagine you are in a supermarket. You have two bananas in your basket and
want to buy four apples. How many fruits do you have in total? This seemingly
straightforward question can be challenging for data-driven language models,
even if trained at scale. However, we would expect such generic language models
to possess some mathematical abilities in addition to typical linguistic
competence. Towards this goal, we investigate if a commonly used language
model, BERT, possesses such mathematical abilities and, if so, to what degree.
For that, we fine-tune BERT on a popular dataset for word math problems,
AQuA-RAT, and conduct several tests to understand learned representations
better. Since we teach models trained on natural language to do formal
mathematics, we hypothesize that such models would benefit from training on
semi-formal steps that explain how math results are derived. To better
accommodate such training, we also propose new pretext tasks for learning
mathematical rules. We call them (Neighbor) Reasoning Order Prediction (ROP or
NROP). With this new model, we achieve significantly better outcomes than
data-driven baselines and even on-par with more tailored models. We also show
how to reduce positional bias in such models.
