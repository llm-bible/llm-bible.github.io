---
layout: publication
title: Pretraining Data Mixtures Enable Narrow Model Selection Capabilities In Transformer Models
authors: Yadlowsky Steve, Doshi Lyric, Tripuraneni Nilesh
conference: "Arxiv"
year: 2023
bibkey: yadlowsky2023pretraining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00871"}
tags: ['Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Transformer models notably large language models (LLMs) have the remarkable ability to perform in45;context learning (ICL) 45;45; to perform new tasks when prompted with unseen input45;output examples without any explicit model training. In this work we study how effectively transformers can bridge between their pretraining data mixture comprised of multiple distinct task families to identify and learn new tasks in45;context which are both inside and outside the pretraining distribution. Building on previous work we investigate this question in a controlled setting where we study transformer models trained on sequences of (x f(x)) pairs rather than natural language. Our empirical results show transformers demonstrate near45;optimal unsupervised model selection capabilities in their ability to first in45;context identify different task families and in45;context learn within them when the task families are well45;represented in their pretraining data. However when presented with tasks or functions which are out45;of45;domain of their pretraining data we demonstrate various failure modes of transformers and degradation of their generalization for even simple extrapolation tasks. Together our results highlight that the impressive ICL abilities of high45;capacity sequence models may be more closely tied to the coverage of their pretraining data mixtures than inductive biases that create fundamental generalization capabilities.
