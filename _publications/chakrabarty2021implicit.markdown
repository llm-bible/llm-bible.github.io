---
layout: publication
title: Implicit Premise Generation With Discourse45;aware Commonsense Knowledge Models
authors: Chakrabarty Tuhin, Trivedi Aadit, Muresan Smaranda
conference: "Arxiv"
year: 2021
bibkey: chakrabarty2021implicit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.05358"}
tags: ['Applications', 'Language Modeling']
---
Enthymemes are defined as arguments where a premise or conclusion is left implicit. We tackle the task of generating the implicit premise in an enthymeme which requires not only an understanding of the stated conclusion and premise but also additional inferences that could depend on commonsense knowledge. The largest available dataset for enthymemes (Habernal et al. 2018) consists of 1.7k samples which is not large enough to train a neural text generation model. To address this issue we take advantage of a similar task and dataset Abductive reasoning in narrative text (Bhagavatula et al. 2020). However we show that simply using a state45;of45;the45;art seq2seq model fine45;tuned on this data might not generate meaningful implicit premises associated with the given enthymemes. We demonstrate that encoding discourse45;aware commonsense during fine45;tuning improves the quality of the generated implicit premises and outperforms all other baselines both in automatic and human evaluations on three different datasets.
