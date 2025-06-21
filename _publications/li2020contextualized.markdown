---
layout: publication
title: Contextualized Perturbation For Textual Adversarial Attack
authors: Dianqi Li et al.
conference: Arxiv
year: 2020
citations: 63
bibkey: li2020contextualized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.07502'}]
tags: [Security, BERT]
---
Adversarial examples expose the vulnerabilities of natural language
processing (NLP) models, and can be used to evaluate and improve their
robustness. Existing techniques of generating such examples are typically
driven by local heuristic rules that are agnostic to the context, often
resulting in unnatural and ungrammatical outputs. This paper presents CLARE, a
ContextuaLized AdversaRial Example generation model that produces fluent and
grammatical outputs through a mask-then-infill procedure. CLARE builds on a
pre-trained masked language model and modifies the inputs in a context-aware
manner. We propose three contextualized perturbations, Replace, Insert and
Merge, allowing for generating outputs of varied lengths. With a richer range
of available strategies, CLARE is able to attack a victim model more
efficiently with fewer edits. Extensive experiments and human evaluation
demonstrate that CLARE outperforms the baselines in terms of attack success
rate, textual similarity, fluency and grammaticality.