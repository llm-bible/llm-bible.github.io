---
layout: publication
title: 'Thisiscompetition At Semeval-2019 Task 9: BERT Is Unstable For Out-of-domain Samples'
authors: Park Cheoneum, Kim Juae, Lee Hyeon-gu, Amplayo Reinald Kim, Kim Harksoo, Seo Jungyun, Lee Changki
conference: "Arxiv"
year: 2019
bibkey: park2019thisiscompetition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1904.03339"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
This paper describes our system, Joint Encoders for Stable Suggestion
Inference (JESSI), for the SemEval 2019 Task 9: Suggestion Mining from Online
Reviews and Forums. JESSI is a combination of two sentence encoders: (a) one
using multiple pre-trained word embeddings learned from log-bilinear regression
(GloVe) and translation (CoVe) models, and (b) one on top of word encodings
from a pre-trained deep bidirectional transformer (BERT). We include a domain
adversarial training module when training for out-of-domain samples. Our
experiments show that while BERT performs exceptionally well for in-domain
samples, several runs of the model show that it is unstable for out-of-domain
samples. The problem is mitigated tremendously by (1) combining BERT with a
non-BERT encoder, and (2) using an RNN-based classifier on top of BERT. Our
final models obtained second place with 77.78% F-Score on Subtask A (i.e.
in-domain) and achieved an F-Score of 79.59% on Subtask B (i.e.
out-of-domain), even without using any additional external data.
