---
layout: publication
title: Boschai 35;64; PLABA 2023 Leveraging Edit Operations In End-to-end Neural Sentence Simplification
authors: Knappich Valentin, Razniewski Simon, Friedrich Annemarie
conference: "Arxiv"
year: 2023
bibkey: knappich2023boschai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01907"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
Automatic simplification can help laypeople to comprehend complex scientific text. Language models are frequently applied to this task by translating from complex to simple language. In this paper we describe our system based on Llama 2 which ranked first in the PLABA shared task addressing the simplification of biomedical text. We find that the large portion of shared tokens between input and output leads to weak training signals and conservatively editing models. To mitigate these issues we propose sentence-level and token-level loss weights. They give higher weight to modified tokens indicated by edit distance and edit operations respectively. We conduct an empirical evaluation on the PLABA dataset and find that both approaches lead to simplifications closer to those created by human annotators (+1.837; / +3.537; SARI) simpler language (-1 / -1.1 FKGL) and more edits (1.6x / 1.8x edit distance) compared to the same model fine-tuned with standard cross entropy. We furthermore show that the hyperparameter λ in token-level loss weights can be used to control the edit distance and the simplicity level (FKGL).
