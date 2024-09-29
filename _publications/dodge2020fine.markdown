---
layout: publication
title: 'Fine-tuning Pretrained Language Models: Weight Initializations, Data Orders, And Early Stopping'
authors: Dodge Jesse, Ilharco Gabriel, Schwartz Roy, Farhadi Ali, Hajishirzi Hannaneh, Smith Noah
conference: "Arxiv"
year: 2020
bibkey: dodge2020fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.06305"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Fine-tuning pretrained contextual word embedding models to supervised downstream tasks has become commonplace in natural language processing. This process however is often brittle even with the same hyperparameter values distinct random seeds can lead to substantially different results. To better understand this phenomenon we experiment with four datasets from the GLUE benchmark fine-tuning BERT hundreds of times on each while varying only the random seeds. We find substantial performance increases compared to previously reported results and we quantify how the performance of the best-found model varies as a function of the number of fine-tuning trials. Further we examine two factors influenced by the choice of random seed weight initialization and training data order. We find that both contribute comparably to the variance of out-of-sample performance and that some weight initializations perform well across all tasks explored. On small datasets we observe that many fine-tuning trials diverge part of the way through training and we offer best practices for practitioners to stop training less promising runs early. We publicly release all of our experimental data including training and validation scores for 2100 trials to encourage further analysis of training dynamics during fine-tuning.
