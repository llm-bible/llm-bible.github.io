---
layout: publication
title: Data Distillation For Controlling Specificity In Dialogue Generation
authors: Jiwei Li, Will Monroe, Dan Jurafsky
conference: Arxiv
year: 2017
citations: 19
bibkey: li2017data
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.06703'}]
tags: [Distillation, Reinforcement Learning, Agentic, Efficiency and Optimization]
---
People speak at different levels of specificity in different situations.
Depending on their knowledge, interlocutors, mood, etc.\} A conversational agent
should have this ability and know when to be specific and when to be general.
We propose an approach that gives a neural network--based conversational agent
this ability. Our approach involves alternating between *data
distillation* and model training : removing training examples that are closest
to the responses most commonly produced by the model trained from the last
round and then retrain the model on the remaining dataset. Dialogue generation
models trained with different degrees of data distillation manifest different
levels of specificity.
  We then train a reinforcement learning system for selecting among this pool
of generation models, to choose the best level of specificity for a given
input. Compared to the original generative model trained without distillation,
the proposed system is capable of generating more interesting and
higher-quality responses, in addition to appropriately adjusting specificity
depending on the context.
  Our research constitutes a specific case of a broader approach involving
training multiple subsystems from a single dataset distinguished by differences
in a specific property one wishes to model. We show that from such a set of
subsystems, one can use reinforcement learning to build a system that tailors
its output to different input contexts at test time.