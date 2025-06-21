---
layout: publication
title: Retrieval-based Neural Code Generation
authors: Shirley Anugrah Hayati et al.
conference: Arxiv
year: 2018
citations: 40
bibkey: hayati2018retrieval
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.10025'}]
tags: [RAG, Applications]
---
In models to generate program source code from natural language, representing
this code in a tree structure has been a common approach. However, existing
methods often fail to generate complex code correctly due to a lack of ability
to memorize large and complex structures. We introduce ReCode, a method based
on subtree retrieval that makes it possible to explicitly reference existing
code examples within a neural code generation model. First, we retrieve
sentences that are similar to input sentences using a dynamic-programming-based
sentence similarity scoring method. Next, we extract n-grams of action
sequences that build the associated abstract syntax tree. Finally, we increase
the probability of actions that cause the retrieved n-gram action subtree to be
in the predicted code. We show that our approach improves the performance on
two code generation tasks by up to +2.6 BLEU.