---
layout: publication
title: 'Investigating Markers And Drivers Of Gender Bias In Machine Translations'
authors: Peter J Edinburgh Napier University Barclay, Ashkan Edinburgh Napier University Sami
conference: "Arxiv"
year: 2024
bibkey: barclay2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11896"}
tags: ['Ethics and Bias', 'Applications', 'Tools', 'Reinforcement Learning']
---
Implicit gender bias in Large Language Models (LLMs) is a well-documented
problem, and implications of gender introduced into automatic translations can
perpetuate real-world biases. However, some LLMs use heuristics or
post-processing to mask such bias, making investigation difficult. Here, we
examine bias in LLMss via back-translation, using the DeepL translation API to
investigate the bias evinced when repeatedly translating a set of 56 Software
Engineering tasks used in a previous study. Each statement starts with 'she',
and is translated first into a 'genderless' intermediate language then back
into English; we then examine pronoun-choice in the back-translated texts. We
expand prior research in the following ways: (1) by comparing results across
five intermediate languages, namely Finnish, Indonesian, Estonian, Turkish and
Hungarian; (2) by proposing a novel metric for assessing the variation in
gender implied in the repeated translations, avoiding the over-interpretation
of individual pronouns, apparent in earlier work; (3) by investigating sentence
features that drive bias; (4) and by comparing results from three time-lapsed
datasets to establish the reproducibility of the approach. We found that some
languages display similar patterns of pronoun use, falling into three loose
groups, but that patterns vary between groups; this underlines the need to work
with multiple languages. We also identify the main verb appearing in a sentence
as a likely significant driver of implied gender in the translations. Moreover,
we see a good level of replicability in the results, and establish that our
variation metric proves robust despite an obvious change in the behaviour of
the DeepL translation API during the course of the study. These results show
that the back-translation method can provide further insights into bias in
language models.
