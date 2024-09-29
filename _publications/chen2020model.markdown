---
layout: publication
title: Model Selection for Cross-Lingual Transfer
authors: Chen Yang, Ritter Alan
conference: "Arxiv"
year: 2020
bibkey: chen2020model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.06127"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Transformers that are pre-trained on multilingual corpora such as mBERT and XLM-RoBERTa have achieved impressive cross-lingual transfer capabilities. In the zero-shot transfer setting only English training data is used and the fine-tuned model is evaluated on another target language. While this works surprisingly well substantial variance has been observed in target language performance between different fine-tuning runs and in the zero-shot setup no target-language development data is available to select among multiple fine-tuned models. Prior work has relied on English dev data to select among models that are fine-tuned with different learning rates number of steps and other hyperparameters often resulting in suboptimal choices. In this paper we show that it is possible to select consistently better models when small amounts of annotated data are available in auxiliary pivot languages. We propose a machine learning approach to model selection that uses the fine-tuned models own internal representations to predict its cross-lingual capabilities. In extensive experiments we find that this method consistently selects better models than English validation data across twenty five languages (including eight low-resource languages) and often achieves results that are comparable to model selection using target language development data.
