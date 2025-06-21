---
layout: publication
title: 'Conversing By Reading: Contentful Neural Conversation With On-demand Machine
  Reading'
authors: Lianhui Qin et al.
conference: Arxiv
year: 2019
citations: 30
bibkey: qin2019conversing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.02738'}]
tags: [Reinforcement Learning, RAG]
---
Although neural conversation models are effective in learning how to produce
fluent responses, their primary challenge lies in knowing what to say to make
the conversation contentful and non-vacuous. We present a new end-to-end
approach to contentful neural conversation that jointly models response
generation and on-demand machine reading. The key idea is to provide the
conversation model with relevant long-form text on the fly as a source of
external knowledge. The model performs QA-style reading comprehension on this
text in response to each conversational turn, thereby allowing for more focused
integration of external knowledge than has been possible in prior approaches.
To support further research on knowledge-grounded conversation, we introduce a
new large-scale conversation dataset grounded in external web pages (2.8M
turns, 7.4M sentences of grounding). Both human evaluation and automated
metrics show that our approach results in more contentful responses compared to
a variety of previous methods, improving both the informativeness and diversity
of generated output.