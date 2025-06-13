---
layout: publication
title: 'Multi-scale Quasi-rnn For Next Item Recommendation'
authors: Chaoyue He, Yong Liu, Qingyu Guo, Chunyan Miao
conference: "Arxiv"
year: 2019
bibkey: he2019multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1902.09849'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'RecSys', 'Model Architecture']
---
How to better utilize sequential information has been extensively studied in
the setting of recommender systems. To this end, architectural inductive biases
such as Markov-Chains, Recurrent models, Convolutional networks and many others
have demonstrated reasonable success on this task. This paper proposes a new
neural architecture, multi-scale Quasi-RNN for next item Recommendation
(QR-Rec) task. Our model provides the best of both worlds by exploiting
multi-scale convolutional features as the compositional gating functions of a
recurrent cell. The model is implemented in a multi-scale fashion, i.e.,
convolutional filters of various widths are implemented to capture different
union-level features of input sequences which influence the compositional
encoder. The key idea aims to capture the recurrent relations between different
kinds of local features, which has never been studied previously in the context
of recommendation. Through extensive experiments, we demonstrate that our model
achieves state-of-the-art performance on 15 well-established datasets,
outperforming strong competitors such as FPMC, Fossil and Caser absolutely by
0.57%-7.16% and relatively by 1.44%-17.65% in terms of MAP, Recall@10 and
NDCG@10.
