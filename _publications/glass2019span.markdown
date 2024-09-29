---
layout: publication
title: Span Selection Pre45;training For Question Answering
authors: Glass Michael, Gliozzo Alfio, Chakravarti Rishav, Ferritto Anthony, Pan Lin, Bhargav G P Shrivatsa, Garg Dinesh, Sil Avirup
conference: "Arxiv"
year: 2019
bibkey: glass2019span
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.04120"}
tags: ['Applications', 'BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
BERT (Bidirectional Encoder Representations from Transformers) and related pre45;trained Transformers have provided large gains across many language understanding tasks achieving a new state45;of45;the45;art (SOTA). BERT is pre45;trained on two auxiliary tasks Masked Language Model and Next Sentence Prediction. In this paper we introduce a new pre45;training task inspired by reading comprehension to better align the pre45;training from memorization to understanding. Span Selection Pre45;Training (SSPT) poses cloze45;like training instances but rather than draw the answer from the models parameters it is selected from a relevant passage. We find significant and consistent improvements over both BERT45;BASE and BERT45;LARGE on multiple reading comprehension (MRC) datasets. Specifically our proposed model has strong empirical evidence as it obtains SOTA results on Natural Questions a new benchmark MRC dataset outperforming BERT45;LARGE by 3 F1 points on short answer prediction. We also show significant impact in HotpotQA improving answer prediction F1 by 4 points and supporting fact prediction F1 by 1 point and outperforming the previous best system. Moreover we show that our pre45;training approach is particularly effective when training data is limited improving the learning curve by a large amount.
