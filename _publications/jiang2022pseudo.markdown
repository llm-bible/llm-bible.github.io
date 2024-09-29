---
layout: publication
title: Pseudo45;q Generating Pseudo Language Queries For Visual Grounding
authors: Jiang Haojun, Lin Yuanze, Han Dongchen, Song Shiji, Huang Gao
conference: "Arxiv"
year: 2022
bibkey: jiang2022pseudo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.08481"}
  - {name: "Code", url: "https://github.com/LeapLabTHU/Pseudo&#45;Q"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Visual grounding i.e. localizing objects in images according to natural language queries is an important topic in visual language understanding. The most effective approaches for this task are based on deep learning which generally require expensive manually labeled image45;query or patch45;query pairs. To eliminate the heavy dependence on human annotations we present a novel method named Pseudo45;Q to automatically generate pseudo language queries for supervised training. Our method leverages an off45;the45;shelf object detector to identify visual objects from unlabeled images and then language queries for these objects are obtained in an unsupervised fashion with a pseudo45;query generation module. Then we design a task45;related query prompt module to specifically tailor generated pseudo language queries for visual grounding tasks. Further in order to fully capture the contextual relationships between images and language queries we develop a visual45;language model equipped with multi45;level cross45;modality attention mechanism. Extensive experimental results demonstrate that our method has two notable benefits (1) it can reduce human annotation costs significantly e.g. 3137; on RefCOCO without degrading original models performance under the fully supervised setting and (2) without bells and whistles it achieves superior or comparable performance compared to state45;of45;the45;art weakly45;supervised visual grounding methods on all the five datasets we have experimented. Code is available at https://github.com/LeapLabTHU/Pseudo&#45;Q.
