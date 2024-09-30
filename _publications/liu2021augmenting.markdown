---
layout: publication
title: 'Augmenting Sequential Recommendation With Pseudo-prior Items Via Reversely Pre-training Transformer'
authors: Liu Zhiwei, Fan Ziwei, Wang Yu, Yu Philip S.
conference: "Arxiv"
year: 2021
bibkey: liu2021augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.00522"}
  - {name: "Code", url: "https://github.com/DyGRec/ASReP"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Sequential Recommendation characterizes the evolving patterns by modeling item sequences chronologically. The essential target of it is to capture the item transition correlations. The recent developments of transformer inspire the community to design effective sequence encoders textite.g. SASRec and BERT4Rec. However we observe that these transformer-based models suffer from the cold-start issue textiti.e. performing poorly for short sequences. Therefore we propose to augment short sequences while still preserving original sequential correlations. We introduce a new framework for textbfAugmenting textbfSequential textbfRecommendation with textbfPseudo-prior items~(ASReP). We firstly pre-train a transformer with sequences in a reverse direction to predict prior items. Then we use this transformer to generate fabricated historical items at the beginning of short sequences. Finally we fine-tune the transformer using these augmented sequences from the time order to predict the next item. Experiments on two real-world datasets verify the effectiveness of ASReP. The code is available on urlhttps://github.com/DyGRec/ASReP\}."
