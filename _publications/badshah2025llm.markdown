---
layout: publication
title: 'DAFE: Llm-based Evaluation Through Dynamic Arbitration For Free-form Question-answering'
authors: Sher Badshah, Hassan Sajjad
conference: "Arxiv"
year: 2025
bibkey: badshah2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08542'}
tags: ['RAG', 'Tools']
---
Evaluating Large Language Models (LLMs) free-form generated responses remains
a challenge due to their diverse and open-ended nature. Traditional supervised
signal-based automatic metrics fail to capture semantic equivalence or handle
the variability of open-ended responses, while human evaluation, though
reliable, is resource-intensive. Leveraging LLMs as evaluators offers a
promising alternative due to their strong language understanding and
instruction-following capabilities. Taking advantage of these capabilities, we
propose the Dynamic Arbitration Framework for Evaluation (DAFE), which employs
two primary LLM-as-judges and engages a third arbitrator only in cases of
disagreements. This selective arbitration prioritizes evaluation reliability
while reducing unnecessary computational demands compared to conventional
majority voting. DAFE utilizes task-specific reference answers with dynamic
arbitration to enhance judgment accuracy, resulting in significant improvements
in evaluation metrics such as Macro F1 and Cohen's Kappa. Through experiments,
including a comprehensive human evaluation, we demonstrate DAFE's ability to
provide consistent, scalable, and resource-efficient assessments, establishing
it as a robust framework for evaluating free-form model outputs.
