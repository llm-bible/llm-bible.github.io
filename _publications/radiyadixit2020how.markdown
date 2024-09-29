---
layout: publication
title: 'How Fine Can Fine-tuning Be? Learning Efficient Language Models'
authors: Radiya-dixit Evani, Wang Xin
conference: "Arxiv"
year: 2020
bibkey: radiyadixit2020how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.14129"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
State-of-the-art performance on language understanding tasks is now achieved with increasingly large networks; the current record holder has billions of parameters. Given a language model pre-trained on massive unlabeled text corpora only very light supervised fine-tuning is needed to learn a task the number of fine-tuning steps is typically five orders of magnitude lower than the total parameter count. Does this mean that fine-tuning only introduces small differences from the pre-trained model in the parameter space If so can one avoid storing and computing an entire model for each task In this work we address these questions by using Bidirectional Encoder Representations from Transformers (BERT) as an example. As expected we find that the fine-tuned models are close in parameter space to the pre-trained one with the closeness varying from layer to layer. We show that it suffices to fine-tune only the most critical layers. Further we find that there are surprisingly many good solutions in the set of sparsified versions of the pre-trained model. As a result fine-tuning of huge language models can be achieved by simply setting a certain number of entries in certain layers of the pre-trained parameters to zero saving both task-specific parameter storage and computational cost.
