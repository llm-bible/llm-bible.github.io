---
layout: publication
title: 'Rejected Dialects: Biases Against African American Language In Reward Models'
authors: Joel Mire, Zubin Trivadi Aysola, Daniel Chechelnitsky, Nicholas Deas, Chrysoula Zerva, Maarten Sap
conference: "Arxiv"
year: 2025
bibkey: mire2025rejected
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12858'}
tags: ['RAG', 'Fairness', 'Tools', 'Prompting', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias']
---
Preference alignment via reward models helps build safe, helpful, and
reliable large language models (LLMs). However, subjectivity in preference
judgments and the lack of representative sampling in preference data collection
can introduce new biases, hindering reward models' fairness and equity. In this
work, we introduce a framework for evaluating dialect biases in reward models
and conduct a case study on biases against African American Language (AAL)
through several experiments comparing reward model preferences and behavior on
paired White Mainstream English (WME) and both machine-translated and
human-written AAL corpora. We show that reward models are less aligned with
human preferences when processing AAL texts vs. WME ones (-4% accuracy on
average), frequently disprefer AAL-aligned texts vs. WME-aligned ones, and
steer conversations toward WME, even when prompted with AAL texts. Our findings
provide a targeted analysis of anti-AAL biases at a relatively understudied
stage in LLM development, highlighting representational harms and ethical
questions about the desired behavior of LLMs concerning AAL.
