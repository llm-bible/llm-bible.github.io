---
layout: publication
title: 'DP-KB: Data Programming With Knowledge Bases Improves Transformer Fine Tuning For Answer Sentence Selection'
authors: Jedema Nic, Vu Thuy, Gupta Manish, Moschitti Alessandro
conference: "Arxiv"
year: 2022
bibkey: jedema2022dp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.09598"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
'While transformers demonstrate impressive performance on many knowledge intensive (KI) tasks, their ability to serve as implicit knowledge bases (KBs) remains limited, as shown on several slot-filling, question-answering (QA), fact verification, and entity-linking tasks. In this paper, we implement an efficient, data-programming technique that enriches training data with KB-derived context and improves transformer utilization of encoded knowledge when fine-tuning for a particular QA task, namely answer sentence selection (AS2). Our method outperforms state of the art transformer approach on WikiQA and TrecQA, two widely studied AS2 benchmarks, increasing by 2.0&#37; p@1, 1.3&#37; MAP, 1.1&#37; MRR, and 4.4&#37; p@1, 0.9&#37; MAP, 2.4&#37; MRR, respectively. To demonstrate our improvements in an industry setting, we additionally evaluate our approach on a proprietary dataset of Alexa QA pairs, and show increase of 2.3&#37; F1 and 2.0&#37; MAP. We additionally find that these improvements remain even when KB context is omitted at inference time, allowing for the use of our models within existing transformer workflows without additional latency or deployment costs.'
