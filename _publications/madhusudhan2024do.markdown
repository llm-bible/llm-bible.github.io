---
layout: publication
title: 'Do Llms Know When To NOT Answer? Investigating Abstention Abilities Of Large Language Models'
authors: Nishanth Madhusudhan, Sathwik Tejaswi Madhusudhan, Vikas Yadav, Masoud Hashemi
conference: "Arxiv"
year: 2024
bibkey: madhusudhan2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16221"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Merging']
---
Abstention Ability (AA) is a critical aspect of Large Language Model (LLM)
reliability, referring to an LLM's capability to withhold responses when
uncertain or lacking a definitive answer, without compromising performance.
Although previous studies have attempted to improve AA, they lack a
standardised evaluation method and remain unsuitable for black-box models where
token prediction probabilities are inaccessible. This makes comparative
analysis challenging, especially for state-of-the-art closed-source commercial
LLMs. This paper bridges this gap by introducing a black-box evaluation
approach and a new dataset, Abstain-QA, crafted to rigorously assess AA across
varied question types (answerable and unanswerable), domains (well-represented
and under-represented), and task types (fact centric and reasoning). We also
propose a new confusion matrix, the ''Answerable-Unanswerable Confusion
Matrix'' (AUCM) which serves as the basis for evaluating AA, by offering a
structured and precise approach for assessment. Finally, we explore the impact
of three prompting strategies-Strict Prompting, Verbal Confidence Thresholding,
and Chain-of-Thought (CoT)-on improving AA. Our results indicate that even
powerful models like GPT-4, Mixtral 8x22b encounter difficulties with
abstention; however, strategic approaches such as Strict prompting and CoT can
enhance this capability.
