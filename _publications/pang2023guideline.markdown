---
layout: publication
title: 'Guideline Learning For In-context Information Extraction'
authors: Chaoxu Pang, Yixuan Cao, Qiang Ding, Ping Luo
conference: "Arxiv"
year: 2023
bibkey: pang2023guideline
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05066"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Attention Mechanism', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) can perform a new task by merely conditioning on
task instructions and a few input-output examples, without optimizing any
parameters. This is called In-Context Learning (ICL). In-context Information
Extraction (IE) has recently garnered attention in the research community.
However, the performance of In-context IE generally lags behind the
state-of-the-art supervised expert models. We highlight a key reason for this
shortfall: underspecified task description. The limited-length context
struggles to thoroughly express the intricate IE task instructions and various
edge cases, leading to misalignment in task comprehension with humans. In this
paper, we propose a Guideline Learning (GL) framework for In-context IE which
reflectively learns and follows guidelines. During the learning phrase, GL
automatically synthesizes a set of guidelines based on a few error cases, and
during inference, GL retrieves helpful guidelines for better ICL. Moreover, we
propose a self-consistency-based active learning method to enhance the
efficiency of GL. Experiments on event extraction and relation extraction show
that GL can significantly improve the performance of in-context IE.
