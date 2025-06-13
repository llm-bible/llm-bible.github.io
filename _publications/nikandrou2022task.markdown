---
layout: publication
title: 'Task Formulation Matters When Learning Continually: A Case Study In Visual Question Answering'
authors: Mavina Nikandrou, Lu Yu, Alessandro Suglia, Ioannis Konstas, Verena Rieser
conference: "Arxiv"
year: 2022
bibkey: nikandrou2022task
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.00044'}
tags: ['Transformer', 'Security', 'Model Architecture', 'Applications', 'Pretraining Methods']
---
Continual learning aims to train a model incrementally on a sequence of tasks
without forgetting previous knowledge. Although continual learning has been
widely studied in computer vision, its application to Vision+Language tasks is
not that straightforward, as settings can be parameterized in multiple ways
according to their input modalities. In this paper, we present a detailed study
of how different settings affect performance for Visual Question Answering. We
first propose three plausible task formulations and demonstrate their impact on
the performance of continual learning algorithms. We break down several factors
of task similarity, showing that performance and sensitivity to task order
highly depend on the shift of the output distribution. We also investigate the
potential of pretrained models and compare the robustness of transformer models
with different visual embeddings. Finally, we provide an analysis interpreting
model representations and their impact on forgetting. Our results highlight the
importance of stabilizing visual representations in deeper layers.
