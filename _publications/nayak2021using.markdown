---
layout: publication
title: 'Using Integrated Gradients And Constituency Parse Trees To Explain Linguistic Acceptability Learnt By BERT'
authors: Anmol Nayak, Hari Prasad Timmapathini
conference: "Arxiv"
year: 2021
bibkey: nayak2021using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.07349"}
tags: ['RAG', 'BERT', 'Applications', 'Model Architecture']
---
Linguistic Acceptability is the task of determining whether a sentence is
grammatical or ungrammatical. It has applications in several use cases like
Question-Answering, Natural Language Generation, Neural Machine Translation,
where grammatical correctness is crucial. In this paper we aim to understand
the decision-making process of BERT (Devlin et al., 2019) in distinguishing
between Linguistically Acceptable sentences (LA) and Linguistically
Unacceptable sentences (LUA). We leverage Layer Integrated Gradients
Attribution Scores (LIG) to explain the Linguistic Acceptability criteria that
are learnt by BERT on the Corpus of Linguistic Acceptability (CoLA) (Warstadt
et al., 2018) benchmark dataset. Our experiments on 5 categories of sentences
lead to the following interesting findings: 1) LIG for LA are significantly
smaller in comparison to LUA, 2) There are specific subtrees of the
Constituency Parse Tree (CPT) for LA and LUA which contribute larger LIG, 3)
Across the different categories of sentences we observed around 88% to 100% of
the Correctly classified sentences had positive LIG, indicating a strong
positive relationship to the prediction confidence of the model, and 4) Around
43% of the Misclassified sentences had negative LIG, which we believe can
become correctly classified sentences if the LIG are parameterized in the loss
function of the model.
