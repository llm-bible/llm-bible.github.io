---
layout: publication
title: 'Self-consistency Falls Short! The Adverse Effects Of Positional Bias On Long-context Problems'
authors: Adam Byerly, Daniel Khashabi
conference: "Arxiv"
year: 2024
bibkey: byerly2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01101"}
tags: ['Prompting', 'Ethics and Bias', 'Reinforcement Learning']
---
Self-consistency (SC) has been demonstrated to enhance the performance of
large language models (LLMs) across various tasks and domains involving short
content. However, does this evidence support its effectiveness for long-context
problems?
  We challenge the assumption that SC's benefits generalize to long-context
settings, where LLMs often struggle with position bias--a systematic tendency
to over-rely on specific context regions-which hinders their ability to utilize
information effectively from all parts of their context. Through comprehensive
experimentation with varying state-of-the-art models and tasks, we find that SC
not only fails to improve but actively degrades performance on long-context
tasks. This degradation appears driven by persistent position bias, worsening
with longer context lengths and smaller model sizes, but invariant to prompt
format or task type. Unlike short-context tasks, where SC diversifies reasoning
paths, long-context SC amplifies positional errors. These comprehensive results
provide valuable insight into the limitations of current LLMs in long-context
understanding and highlight the need for more sophisticated approaches.
