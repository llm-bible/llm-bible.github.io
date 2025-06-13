---
layout: publication
title: 'DERA: Enhancing Large Language Model Completions With Dialog-enabled Resolving Agents'
authors: Varun Nair, Elliot Schumacher, Geoffrey Tso, Anitha Kannan
conference: "Arxiv"
year: 2023
bibkey: nair2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.17071"}
  - {name: "Code", url: "https://github.com/curai/curai-research/tree/main/DERA"}
tags: ['Responsible AI', 'Agentic', 'Model Architecture', 'Tools', 'GPT', 'Has Code', 'Applications']
---
Large language models (LLMs) have emerged as valuable tools for many natural
language understanding tasks. In safety-critical applications such as
healthcare, the utility of these models is governed by their ability to
generate outputs that are factually accurate and complete. In this work, we
present dialog-enabled resolving agents (DERA). DERA is a paradigm made
possible by the increased conversational abilities of LLMs, namely GPT-4. It
provides a simple, interpretable forum for models to communicate feedback and
iteratively improve output. We frame our dialog as a discussion between two
agent types - a Researcher, who processes information and identifies crucial
problem components, and a Decider, who has the autonomy to integrate the
Researcher's information and makes judgments on the final output.
  We test DERA against three clinically-focused tasks. For medical conversation
summarization and care plan generation, DERA shows significant improvement over
the base GPT-4 performance in both human expert preference evaluations and
quantitative metrics. In a new finding, we also show that GPT-4's performance
(70%) on an open-ended version of the MedQA question-answering (QA) dataset
(Jin et al. 2021, USMLE) is well above the passing level (60%), with DERA
showing similar performance. We release the open-ended MEDQA dataset at
https://github.com/curai/curai-research/tree/main/DERA.
