---
layout: publication
title: 'Validating Large Language Models With Relm'
authors: Kuchnik Michael, Smith Virginia, Amvrosiadis George
conference: "Arxiv"
year: 2022
bibkey: kuchnik2022validating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.15458"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Prompting', 'RAG']
---
Although large language models (LLMs) have been touted for their ability to
generate natural-sounding text, there are growing concerns around possible
negative effects of LLMs such as data memorization, bias, and inappropriate
language. Unfortunately, the complexity and generation capacities of LLMs make
validating (and correcting) such concerns difficult. In this work, we introduce
ReLM, a system for validating and querying LLMs using standard regular
expressions. ReLM formalizes and enables a broad range of language model
evaluations, reducing complex evaluation rules to simple regular expression
queries. Our results exploring queries surrounding memorization, gender bias,
toxicity, and language understanding show that ReLM achieves up to 15x higher
system efficiency, 2.5x data efficiency, and increased statistical and
prompt-tuning coverage compared to state-of-the-art ad-hoc queries. ReLM offers
a competitive and general baseline for the increasingly important problem of
LLM validation.
