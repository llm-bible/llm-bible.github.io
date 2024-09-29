---
layout: publication
title: Thisiscompetition At Semeval45;2019 Task 9 BERT Is Unstable For Out45;of45;domain Samples
authors: Park Cheoneum, Kim Juae, Lee Hyeon-gu, Amplayo Reinald Kim, Kim Harksoo, Seo Jungyun, Lee Changki
conference: "Arxiv"
year: 2019
bibkey: park2019thisiscompetition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1904.03339"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
This paper describes our system Joint Encoders for Stable Suggestion Inference (JESSI) for the SemEval 2019 Task 9 Suggestion Mining from Online Reviews and Forums. JESSI is a combination of two sentence encoders (a) one using multiple pre45;trained word embeddings learned from log45;bilinear regression (GloVe) and translation (CoVe) models and (b) one on top of word encodings from a pre45;trained deep bidirectional transformer (BERT). We include a domain adversarial training module when training for out45;of45;domain samples. Our experiments show that while BERT performs exceptionally well for in45;domain samples several runs of the model show that it is unstable for out45;of45;domain samples. The problem is mitigated tremendously by (1) combining BERT with a non45;BERT encoder and (2) using an RNN45;based classifier on top of BERT. Our final models obtained second place with 77.7837; F45;Score on Subtask A (i.e. in45;domain) and achieved an F45;Score of 79.5937; on Subtask B (i.e. out45;of45;domain) even without using any additional external data.
