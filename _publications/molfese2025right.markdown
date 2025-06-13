---
layout: publication
title: 'Right Answer, Wrong Score: Uncovering The Inconsistencies Of LLM Evaluation In Multiple-choice Question Answering'
authors: Francesco Maria Molfese, Luca Moroni, Luca Gioffrè, Alessandro Scirè, Simone Conia, Roberto Navigli
conference: "Arxiv"
year: 2025
bibkey: molfese2025right
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.14996'}
tags: ['Prompting', 'Applications']
---
One of the most widely used tasks to evaluate Large Language Models (LLMs) is
Multiple-Choice Question Answering (MCQA). While open-ended question answering
tasks are more challenging to evaluate, MCQA tasks are, in principle, easier to
assess, as the model's answer is thought to be simple to extract and is
directly compared to a set of predefined choices. However, recent studies have
started to question the reliability of MCQA evaluation, showing that multiple
factors can significantly impact the reported performance of LLMs, especially
when the model generates free-form text before selecting one of the answer
choices. In this work, we shed light on the inconsistencies of MCQA evaluation
strategies, which can lead to inaccurate and misleading model comparisons. We
systematically analyze whether existing answer extraction methods are aligned
with human judgment, and how they are influenced by answer constraints in the
prompt across different domains. Our experiments demonstrate that traditional
evaluation strategies often underestimate LLM capabilities, while LLM-based
answer extractors are prone to systematic errors. Moreover, we reveal a
fundamental trade-off between including format constraints in the prompt to
simplify answer extraction and allowing models to generate free-form text to
improve reasoning. Our findings call for standardized evaluation methodologies
and highlight the need for more reliable and consistent MCQA evaluation
practices.
