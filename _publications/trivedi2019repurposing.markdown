---
layout: publication
title: "Repurposing Entailment For Multi-hop Question Answering Tasks"
authors: Trivedi Harsh, Kwon Heeyoung, Khot Tushar, Sabharwal Ashish, Balasubramanian Niranjan
conference: "Arxiv"
year: 2019
bibkey: trivedi2019repurposing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1904.09380"}
  - {name: "Code", url: "https://github.com/StonyBrookNLP/multee"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Question Answering (QA) naturally reduces to an entailment problem namely verifying whether some text entails the answer to a question. However for multi-hop QA tasks which require reasoning with multiple sentences it remains unclear how best to utilize entailment models pre-trained on large scale datasets such as SNLI which are based on sentence pairs. We introduce Multee a general architecture that can effectively use entailment models for multi-hop QA tasks. Multee uses (i) a local module that helps locate important sentences thereby avoiding distracting information and (ii) a global module that aggregates information by effectively incorporating importance weights. Importantly we show that both modules can use entailment functions pre-trained on a large scale NLI datasets. We evaluate performance on MultiRC and OpenBookQA two multihop QA datasets. When using an entailment function pre-trained on NLI datasets Multee outperforms QA models trained only on the target QA datasets and the OpenAI transformer models. The code is available at https://github.com/StonyBrookNLP/multee."
