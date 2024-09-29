---
layout: publication
title: Augmenting Sequential Recommendation With Pseudo45;prior Items Via Reversely Pre45;training Transformer
authors: Liu Zhiwei, Fan Ziwei, Wang Yu, Yu Philip S.
conference: "Arxiv"
year: 2021
bibkey: liu2021augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.00522"}
  - {name: "Code", url: "https://github.com/DyGRec/ASReP&#125;"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Sequential Recommendation characterizes the evolving patterns by modeling item sequences chronologically. The essential target of it is to capture the item transition correlations. The recent developments of transformer inspire the community to design effective sequence encoders textit123;e.g.125; SASRec and BERT4Rec. However we observe that these transformer45;based models suffer from the cold45;start issue textit123;i.e.125; performing poorly for short sequences. Therefore we propose to augment short sequences while still preserving original sequential correlations. We introduce a new framework for textbf123;A125;ugmenting textbf123;S125;equential textbf123;Re125;commendation with textbf123;P125;seudo45;prior items~(ASReP). We firstly pre45;train a transformer with sequences in a reverse direction to predict prior items. Then we use this transformer to generate fabricated historical items at the beginning of short sequences. Finally we fine45;tune the transformer using these augmented sequences from the time order to predict the next item. Experiments on two real45;world datasets verify the effectiveness of ASReP. The code is available on url123;https://github.com/DyGRec/ASReP&#125;.
