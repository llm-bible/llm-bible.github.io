---
layout: publication
title: Unified Language Model Pre45;training For Natural Language Understanding And Generation
authors: Dong Li, Yang Nan, Wang Wenhui, Wei Furu, Liu Xiaodong, Wang Yu, Gao Jianfeng, Zhou Ming, Hon Hsiao-wuen
conference: "Arxiv"
year: 2019
bibkey: dong2019unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1905.03197"}
  - {name: "Code", url: "https://github.com/microsoft/unilm"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
This paper presents a new Unified pre45;trained Language Model (UniLM) that can be fine45;tuned for both natural language understanding and generation tasks. The model is pre45;trained using three types of language modeling tasks unidirectional bidirectional and sequence45;to45;sequence prediction. The unified modeling is achieved by employing a shared Transformer network and utilizing specific self45;attention masks to control what context the prediction conditions on. UniLM compares favorably with BERT on the GLUE benchmark and the SQuAD 2.0 and CoQA question answering tasks. Moreover UniLM achieves new state45;of45;the45;art results on five natural language generation datasets including improving the CNN/DailyMail abstractive summarization ROUGE45;L to 40.51 (2.04 absolute improvement) the Gigaword abstractive summarization ROUGE45;L to 35.75 (0.86 absolute improvement) the CoQA generative question answering F1 score to 82.5 (37.1 absolute improvement) the SQuAD question generation BLEU45;4 to 22.12 (3.75 absolute improvement) and the DSTC7 document45;grounded dialog response generation NIST45;4 to 2.67 (human performance is 2.65). The code and pre45;trained models are available at https://github.com/microsoft/unilm.
