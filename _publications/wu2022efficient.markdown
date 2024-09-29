---
layout: publication
title: An Efficient Memory45;augmented Transformer For Knowledge45;intensive NLP Tasks
authors: Wu Yuxiang, Zhao Yu, Hu Baotian, Minervini Pasquale, Stenetorp Pontus, Riedel Sebastian
conference: "Arxiv"
year: 2022
bibkey: wu2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.16773"}
  - {name: "Code", url: "https://github"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Access to external knowledge is essential for many natural language processing tasks such as question answering and dialogue. Existing methods often rely on a parametric model that stores knowledge in its parameters or use a retrieval45;augmented model that has access to an external knowledge source. Parametric and retrieval45;augmented models have complementary strengths in terms of computational efficiency and predictive accuracy. To combine the strength of both approaches we propose the Efficient Memory45;Augmented Transformer (EMAT) 45;45; it encodes external knowledge into a key45;value memory and exploits the fast maximum inner product search for memory querying. We also introduce pre45;training tasks that allow EMAT to encode informative key45;value representations and to learn an implicit strategy to integrate multiple memory slots into the transformer. Experiments on various knowledge45;intensive tasks such as question answering and dialogue datasets show that simply augmenting parametric models (T545;base) using our method produces more accurate results (e.g. 25.8 45; 44.3 EM on NQ) while retaining a high throughput (e.g. 1000 queries/s on NQ). Compared to retrieval45;augmented models EMAT runs substantially faster across the board and produces more accurate results on WoW and ELI5. Our code and datasets are available at https://github. com/uclnlp/EMAT.
