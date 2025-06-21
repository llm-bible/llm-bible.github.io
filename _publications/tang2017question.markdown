---
layout: publication
title: Question Answering And Question Generation As Dual Tasks
authors: Duyu Tang, Nan Duan, Tao Qin, Zhao Yan, Ming Zhou
conference: Arxiv
year: 2017
citations: 176
bibkey: tang2017question
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.02027'}]
tags: [RAG, Tools]
---
We study the problem of joint question answering (QA) and question generation
(QG) in this paper.
  Our intuition is that QA and QG have intrinsic connections and these two
tasks could improve each other.
  On one side, the QA model judges whether the generated question of a QG model
is relevant to the answer.
  On the other side, the QG model provides the probability of generating a
question given the answer, which is a useful evidence that in turn facilitates
QA.
  In this paper we regard QA and QG as dual tasks.
  We propose a training framework that trains the models of QA and QG
simultaneously, and explicitly leverages their probabilistic correlation to
guide the training process of both models.
  We implement a QG model based on sequence-to-sequence learning, and a QA
model based on recurrent neural network.
  As all the components of the QA and QG models are differentiable, all the
parameters involved in these two models could be conventionally learned with
back propagation.
  We conduct experiments on three datasets. Empirical results show that our
training framework improves both QA and QG tasks.
  The improved QA model performs comparably with strong baseline approaches on
all three datasets.