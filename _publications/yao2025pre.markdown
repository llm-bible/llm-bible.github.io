---
layout: publication
title: 'Pre-training Vs. Fine-tuning: A Reproducibility Study On Dense Retrieval Knowledge Acquisition'
authors: Zheng Yao, Shuai Wang, Guido Zuccon
conference: "Arxiv"
year: 2025
bibkey: yao2025pre
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07166'}
  - {name: "Code", url: 'https://github.com/ielab/DenseRetriever-Knowledge-Acquisition'}
tags: ['Has Code', 'Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
Dense retrievers utilize pre-trained backbone language models (e.g., BERT, LLaMA) that are fine-tuned via contrastive learning to perform the task of encoding text into sense representations that can be then compared via a shallow similarity operation, e.g. inner product. Recent research has questioned the role of fine-tuning vs. that of pre-training within dense retrievers, specifically arguing that retrieval knowledge is primarily gained during pre-training, meaning knowledge not acquired during pre-training cannot be sub-sequentially acquired via fine-tuning. We revisit this idea here as the claim was only studied in the context of a BERT-based encoder using DPR as representative dense retriever. We extend the previous analysis by testing other representation approaches (comparing the use of CLS tokens with that of mean pooling), backbone architectures (encoder-only BERT vs. decoder-only LLaMA), and additional datasets (MSMARCO in addition to Natural Questions). Our study confirms that in DPR tuning, pre-trained knowledge underpins retrieval performance, with fine-tuning primarily adjusting neuron activation rather than reorganizing knowledge. However, this pattern does not hold universally, such as in mean-pooled (Contriever) and decoder-based (LLaMA) models. We ensure full reproducibility and make our implementation publicly available at https://github.com/ielab/DenseRetriever-Knowledge-Acquisition.
