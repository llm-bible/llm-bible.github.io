---
layout: publication
title: Knowledgeable Salient Span Mask For Enhancing Language Models As Knowledge Base
authors: Wang Cunxiang, Luo Fuli, Li Yanyang, Xu Runxin, Huang Fei, Zhang Yue
conference: "Arxiv"
year: 2022
bibkey: wang2022knowledgeable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.07994"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Pre45;trained language models (PLMs) like BERT have made significant progress in various downstream NLP tasks. However by asking models to do cloze45;style tests recent work finds that PLMs are short in acquiring knowledge from unstructured text. To understand the internal behaviour of PLMs in retrieving knowledge we first define knowledge45;baring (K45;B) tokens and knowledge45;free (K45;F) tokens for unstructured text and ask professional annotators to label some samples manually. Then we find that PLMs are more likely to give wrong predictions on K45;B tokens and attend less attention to those tokens inside the self45;attention module. Based on these observations we develop two solutions to help the model learn more knowledge from unstructured text in a fully self45;supervised manner. Experiments on knowledge45;intensive tasks show the effectiveness of the proposed methods. To our best knowledge we are the first to explore fully self45;supervised learning of knowledge in continual pre45;training.
