---
layout: publication
title: 'Billions Of Parameters Are Worth More Than In-domain Training Data: A Case Study In The Legal Case Entailment Task'
authors: Rosa Guilherme Moraes, Bonifacio Luiz, Jeronymo Vitor, Abonizio Hugo, Lotufo Roberto, Nogueira Rodrigo
conference: "Arxiv"
year: 2022
bibkey: rosa2022billions
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.15172"}
  - {name: "Code", url: "https://github.com/neuralmind-ai/coliee"}
  - {name: "Code", url: "https://neuralsearchx.neuralmind.ai,"}
tags: ['Applications', 'Few Shot', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recent work has shown that language models scaled to billions of parameters, such as GPT-3, perform remarkably well in zero-shot and few-shot scenarios. In this work, we experiment with zero-shot models in the legal case entailment task of the COLIEE 2022 competition. Our experiments show that scaling the number of parameters in a language model improves the F1 score of our previous zero-shot result by more than 6 points, suggesting that stronger zero-shot capability may be a characteristic of larger models, at least for this task. Our 3B-parameter zero-shot model outperforms all models, including ensembles, in the COLIEE 2021 test set and also achieves the best performance of a single model in the COLIEE 2022 competition, second only to the ensemble composed of the 3B model itself and a smaller version of the same model. Despite the challenges posed by large language models, mainly due to latency constraints in real-time applications, we provide a demonstration of our zero-shot monoT5-3b model being used in production as a search engine, including for legal documents. The code for our submission and the demo of our system are available at https://github.com/neuralmind-ai/coliee and https://neuralsearchx.neuralmind.ai, respectively.
