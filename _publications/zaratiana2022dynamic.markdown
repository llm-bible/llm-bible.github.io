---
layout: publication
title: 'Dyrex: Dynamic Query Representation For Extractive Question Answering'
authors: Urchade Zaratiana, Niama El Khbir, Dennis Núñez, Pierre Holat, Nadi Tomeh, Thierry Charnois
conference: "Arxiv"
year: 2022
bibkey: zaratiana2022dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.15048'}
  - {name: "Code", url: 'https://github.com/urchade/DyReX'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Model Architecture', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Extractive question answering (ExQA) is an essential task for Natural
Language Processing. The dominant approach to ExQA is one that represents the
input sequence tokens (question and passage) with a pre-trained transformer,
then uses two learned query vectors to compute distributions over the start and
end answer span positions. These query vectors lack the context of the inputs,
which can be a bottleneck for the model performance. To address this problem,
we propose \textit\{DyREx\}, a generalization of the \textit\{vanilla\} approach
where we dynamically compute query vectors given the input, using an attention
mechanism through transformer layers. Empirical observations demonstrate that
our approach consistently improves the performance over the standard one. The
code and accompanying files for running the experiments are available at
\url\{https://github.com/urchade/DyReX\}.
