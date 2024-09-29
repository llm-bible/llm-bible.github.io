---
layout: publication
title: TAG Boosting Text45;vqa Via Text45;aware Visual Question45;answer Generation
authors: Wang Jun, Gao Mingfei, Hu Yuqian, Selvaraju Ramprasaath R., Ramaiah Chetan, Xu Ran, Jaja Joseph F., Davis Larry S.
conference: "Arxiv"
year: 2022
bibkey: wang2022boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.01813"}
  - {name: "Code", url: "https://github.com/HenryJunW/TAG"}
tags: ['Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Text45;VQA aims at answering questions that require understanding the textual cues in an image. Despite the great progress of existing Text45;VQA methods their performance suffers from insufficient human45;labeled question45;answer (QA) pairs. However we observe that in general the scene text is not fully exploited in the existing datasets 45;45; only a small portion of the text in each image participates in the annotated QA activities. This results in a huge waste of useful information. To address this deficiency we develop a new method to generate high45;quality and diverse QA pairs by explicitly utilizing the existing rich text available in the scene context of each image. Specifically we propose TAG a text45;aware visual question45;answer generation architecture that learns to produce meaningful and accurate QA samples using a multimodal transformer. The architecture exploits underexplored scene text information and enhances scene understanding of Text45;VQA models by combining the generated QA pairs with the initial training data. Extensive experimental results on two well45;known Text45;VQA benchmarks (TextVQA and ST45;VQA) demonstrate that our proposed TAG effectively enlarges the training data that helps improve the Text45;VQA performance without extra labeling effort. Moreover our model outperforms state45;of45;the45;art approaches that are pre45;trained with extra large45;scale data. Code is available at https://github.com/HenryJunW/TAG.
