---
layout: publication
title: 'Aggretriever: A Simple Approach To Aggregate Textual Representations For Robust Dense Passage Retrieval'
authors: Sheng-chieh Lin, Minghan Li, Jimmy Lin
conference: "Arxiv"
year: 2022
bibkey: lin2022simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.00511"}
  - {name: "Code", url: "https://github.com/castorini/dhr"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'BERT', 'Distillation']
---
Pre-trained language models have been successful in many knowledge-intensive
NLP tasks. However, recent work has shown that models such as BERT are not
``structurally ready'' to aggregate textual information into a [CLS] vector for
dense passage retrieval (DPR). This ``lack of readiness'' results from the gap
between language model pre-training and DPR fine-tuning. Previous solutions
call for computationally expensive techniques such as hard negative mining,
cross-encoder distillation, and further pre-training to learn a robust DPR
model. In this work, we instead propose to fully exploit knowledge in a
pre-trained language model for DPR by aggregating the contextualized token
embeddings into a dense vector, which we call agg*. By concatenating vectors
from the [CLS] token and agg*, our Aggretriever model substantially improves
the effectiveness of dense retrieval models on both in-domain and zero-shot
evaluations without introducing substantial training overhead. Code is
available at https://github.com/castorini/dhr
