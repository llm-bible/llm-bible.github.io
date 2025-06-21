---
layout: publication
title: Grounded Textual Entailment
authors: Hoa Trong Vu et al.
conference: Arxiv
year: 2018
citations: 24
bibkey: vu2018grounded
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.05645'}]
tags: [Multimodal Models]
---
Capturing semantic relations between sentences, such as entailment, is a
long-standing challenge for computational semantics. Logic-based models analyse
entailment in terms of possible worlds (interpretations, or situations) where a
premise P entails a hypothesis H iff in all worlds where P is true, H is also
true. Statistical models view this relationship probabilistically, addressing
it in terms of whether a human would likely infer H from P. In this paper, we
wish to bridge these two perspectives, by arguing for a visually-grounded
version of the Textual Entailment task. Specifically, we ask whether models can
perform better if, in addition to P and H, there is also an image
(corresponding to the relevant "world" or "situation"). We use a multimodal
version of the SNLI dataset (Bowman et al., 2015) and we compare "blind" and
visually-augmented models of textual entailment. We show that visual
information is beneficial, but we also conduct an in-depth error analysis that
reveals that current multimodal models are not performing "grounding" in an
optimal fashion.