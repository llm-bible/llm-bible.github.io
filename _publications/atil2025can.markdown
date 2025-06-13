---
layout: publication
title: 'Can Llms Rank The Harmfulness Of Smaller Llms? We Are Not There Yet'
authors: Berk Atil, Vipul Gupta, Sarkar Snigdha Sarathi Das, Rebecca J. Passonneau
conference: "Arxiv"
year: 2025
bibkey: atil2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.05291'}
tags: ['Reinforcement Learning', 'Prompting']
---
Large language models (LLMs) have become ubiquitous, thus it is important to
understand their risks and limitations. Smaller LLMs can be deployed where
compute resources are constrained, such as edge devices, but with different
propensity to generate harmful output. Mitigation of LLM harm typically depends
on annotating the harmfulness of LLM output, which is expensive to collect from
humans. This work studies two questions: How do smaller LLMs rank regarding
generation of harmful content? How well can larger LLMs annotate harmfulness?
We prompt three small LLMs to elicit harmful content of various types, such as
discriminatory language, offensive content, privacy invasion, or negative
influence, and collect human rankings of their outputs. Then, we evaluate three
state-of-the-art large LLMs on their ability to annotate the harmfulness of
these responses. We find that the smaller models differ with respect to
harmfulness. We also find that large LLMs show low to moderate agreement with
humans. These findings underline the need for further work on harm mitigation
in LLMs.
