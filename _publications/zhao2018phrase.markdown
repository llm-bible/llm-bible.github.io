---
layout: publication
title: 'Phrase Table As Recommendation Memory For Neural Machine Translation'
authors: Zhao Yang, Wang Yining, Zhang Jiajun, Zong Chengqing
conference: "Arxiv"
year: 2018
bibkey: zhao2018phrase
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1805.09960"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture']
---
Neural Machine Translation (NMT) has drawn much attention due to its
promising translation performance recently. However, several studies indicate
that NMT often generates fluent but unfaithful translations. In this paper, we
propose a method to alleviate this problem by using a phrase table as
recommendation memory. The main idea is to add bonus to words worthy of
recommendation, so that NMT can make correct predictions. Specifically, we
first derive a prefix tree to accommodate all the candidate target phrases by
searching the phrase translation table according to the source sentence. Then,
we construct a recommendation word set by matching between candidate target
phrases and previously translated target words by NMT. After that, we determine
the specific bonus value for each recommendable word by using the attention
vector and phrase translation probability. Finally, we integrate this bonus
value into NMT to improve the translation results. The extensive experiments
demonstrate that the proposed methods obtain remarkable improvements over the
strong attentionbased NMT.
