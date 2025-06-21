---
layout: publication
title: Measuring Progress On Scalable Oversight For Large Language Models
authors: Samuel R. Bowman et al.
conference: Arxiv
year: 2022
citations: 21
bibkey: bowman2022measuring
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.03540'}]
tags: [RAG]
---
Developing safe and useful general-purpose AI systems will require us to make
progress on scalable oversight: the problem of supervising systems that
potentially outperform us on most skills relevant to the task at hand.
Empirical work on this problem is not straightforward, since we do not yet have
systems that broadly exceed our abilities. This paper discusses one of the
major ways we think about this problem, with a focus on ways it can be studied
empirically. We first present an experimental design centered on tasks for
which human specialists succeed but unaided humans and current general AI
systems fail. We then present a proof-of-concept experiment meant to
demonstrate a key feature of this experimental design and show its viability
with two question-answering tasks: MMLU and time-limited QuALITY. On these
tasks, we find that human participants who interact with an unreliable
large-language-model dialog assistant through chat -- a trivial baseline
strategy for scalable oversight -- substantially outperform both the model
alone and their own unaided performance. These results are an encouraging sign
that scalable oversight will be tractable to study with present models and
bolster recent findings that large language models can productively assist
humans with difficult tasks.