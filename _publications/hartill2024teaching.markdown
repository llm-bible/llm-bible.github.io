---
layout: publication
title: 'Teaching Smaller Language Models To Generalise To Unseen Compositional Questions (full Thesis)'
authors: Tim Hartill
conference: "Arxiv"
year: 2024
bibkey: hartill2024teaching
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.16985'}
tags: ['Training Techniques', 'RAG', 'Applications']
---
Pretrained large Language Models (LLMs) are able to answer questions that are
unlikely to have been encountered during training. However a diversity of
potential applications exist in the broad domain of reasoning systems and
considerations such as latency, cost, available compute resource and internet
connectivity are relevant in determining an appropriate approach. We consider
the setting where some local compute capacity is available at inference time
but internet connectivity is not.
  Similar to a general-purpose LLM, we assume that our much smaller Reasoning
Models may be asked arbitrary questions from unknown distributions, so we focus
on evaluation in an unseen setting. We train our models to answer diverse
questions by instilling an ability to reason over a retrieved context. We
acquire context from two knowledge sources; a Wikipedia corpus queried using a
multi-hop dense retrieval system with novel extensions, and from rationales
generated from a larger Language Model optimised to run in a lower resource
environment.
  Our main contributions: We propose novel methods to show that our model is
capable of answering contextualised questions without memorisation. We
establish a comprehensive set of baseline results on unseen evaluation
datasets. We show that the addition of novel retrieval-augmented training
datasets (RATD) to the training regime of the Reasoning Model significantly
improves results. We demonstrate further significant improvement through the
application of methods for combining knowledge from two sources. The first
method (RR) involves training a novel Rationale Ranking model to score both
generated rationales and retrieved contexts with respect to relevance and
truthfulness. We use the scores to derive combined contexts. We also show that
utilising the RATD datasets enables our model to become proficient at utilising
combined noisy contexts.
