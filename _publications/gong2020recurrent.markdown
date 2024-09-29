---
layout: publication
title: 'Recurrent Chunking Mechanisms For Long-text Machine Reading Comprehension'
authors: Gong Hongyu, Shen Yelong, Yu Dian, Chen Jianshu, Yu Dong
conference: "Arxiv"
year: 2020
bibkey: gong2020recurrent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.08056"}
tags: ['Agentic', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
In this paper we study machine reading comprehension (MRC) on long texts where a model takes as inputs a lengthy document and a question and then extracts a text span from the document as an answer. State-of-the-art models tend to use a pretrained transformer model (e.g. BERT) to encode the joint contextual information of document and question. However these transformer-based models can only take a fixed-length (e.g. 512) text as its input. To deal with even longer text inputs previous approaches usually chunk them into equally-spaced segments and predict answers based on each segment independently without considering the information from other segments. As a result they may form segments that fail to cover the correct answer span or retain insufficient contexts around it which significantly degrades the performance. Moreover they are less capable of answering questions that need cross-segment information. We propose to let a model learn to chunk in a more flexible way via reinforcement learning a model can decide the next segment that it wants to process in either direction. We also employ recurrent mechanisms to enable information to flow across segments. Experiments on three MRC datasets -- CoQA QuAC and TriviaQA -- demonstrate the effectiveness of our proposed recurrent chunking mechanisms we can obtain segments that are more likely to contain complete answers and at the same time provide sufficient contexts around the ground truth answers for better predictions.
