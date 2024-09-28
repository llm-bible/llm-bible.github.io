---
layout: publication
title: Can Transformers Jump Around Right in Natural Language Assessing Performance Transfer from SCAN
authors: Chaabouni Rahma, Dessì Roberto, Kharitonov Eugene
conference: "Arxiv"
year: 2021
bibkey: chaabouni2021can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.01366"}
tags: ['ARXIV', 'Applications', 'Model Architecture', 'NLP', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Despite their practical success modern seq2seq architectures are unable to generalize systematically on several SCAN tasks. Hence it is not clear if SCAN-style compositional generalization is useful in realistic NLP tasks. In this work we study the benefit that such compositionality brings about to several machine translation tasks. We present several focused modifications of Transformer that greatly improve generalization capabilities on SCAN and select one that remains on par with a vanilla Transformer on a standard machine translation (MT) task. Next we study its performance in low-resource settings and on a newly introduced distribution-shifted English-French translation task. Overall we find that improvements of a SCAN-capable model do not directly transfer to the resource-rich MT setup. In contrast in the low-resource setup general modifications lead to an improvement of up to 13.1 BLEU score w.r.t. a vanilla Transformer. Similarly an improvement of 14 in an accuracy-based metric is achieved in the introduced compositional English-French translation task. This provides experimental evidence that the compositional generalization assessed in SCAN is particularly useful in resource-starved and domain-shifted scenarios.
