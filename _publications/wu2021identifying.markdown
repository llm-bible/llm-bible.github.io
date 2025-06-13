---
layout: publication
title: 'Identifying The Limits Of Cross-domain Knowledge Transfer For Pretrained Models'
authors: Zhengxuan Wu, Nelson F. Liu, Christopher Potts
conference: "Arxiv"
year: 2021
bibkey: wu2021identifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.08410"}
tags: ['Fine-Tuning', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
There is growing evidence that pretrained language models improve
task-specific fine-tuning not just for the languages seen in pretraining, but
also for new languages and even non-linguistic data. What is the nature of this
surprising cross-domain transfer? We offer a partial answer via a systematic
exploration of how much transfer occurs when models are denied any information
about word identity via random scrambling. In four classification tasks and two
sequence labeling tasks, we evaluate baseline models, LSTMs using GloVe
embeddings, and BERT. We find that only BERT shows high rates of transfer into
our scrambled domains, and for classification but not sequence labeling tasks.
Our analyses seek to explain why transfer succeeds for some tasks but not
others, to isolate the separate contributions of pretraining versus
fine-tuning, and to quantify the role of word frequency. These findings help
explain where and why cross-domain transfer occurs, which can guide future
studies and practical fine-tuning efforts.
