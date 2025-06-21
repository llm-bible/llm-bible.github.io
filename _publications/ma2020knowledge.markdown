---
layout: publication
title: Knowledge-driven Data Construction For Zero-shot Evaluation In Commonsense
  Question Answering
authors: Kaixin Ma et al.
conference: Arxiv
year: 2020
citations: 22
bibkey: ma2020knowledge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.03863'}]
tags: [Language Modeling, Pre-Training]
---
Recent developments in pre-trained neural language modeling have led to leaps
in accuracy on commonsense question-answering benchmarks. However, there is
increasing concern that models overfit to specific tasks, without learning to
utilize external knowledge or perform general semantic reasoning. In contrast,
zero-shot evaluations have shown promise as a more robust measure of a model's
general reasoning abilities. In this paper, we propose a novel neuro-symbolic
framework for zero-shot question answering across commonsense tasks. Guided by
a set of hypotheses, the framework studies how to transform various
pre-existing knowledge resources into a form that is most effective for
pre-training models. We vary the set of language models, training regimes,
knowledge sources, and data generation strategies, and measure their impact
across tasks. Extending on prior work, we devise and compare four constrained
distractor-sampling strategies. We provide empirical results across five
commonsense question-answering tasks with data generated from five external
knowledge resources. We show that, while an individual knowledge graph is
better suited for specific tasks, a global knowledge graph brings consistent
gains across different tasks. In addition, both preserving the structure of the
task as well as generating fair and informative questions help language models
learn more effectively.