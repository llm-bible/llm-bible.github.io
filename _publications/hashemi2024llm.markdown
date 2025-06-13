---
layout: publication
title: 'Llm-rubric: A Multidimensional, Calibrated Approach To Automated Evaluation Of Natural Language Texts'
authors: Helia Hashemi, Jason Eisner, Corby Rosset, Benjamin Van Durme, Chris Kedzie
conference: "Proceedings of ACL 2024 (Volume 1 Long Papers) pp. 13806-13834"
year: 2024
bibkey: hashemi2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00274"}
tags: ['Training Techniques', 'Prompting', 'Applications', 'Tools']
---
This paper introduces a framework for the automated evaluation of natural
language texts. A manually constructed rubric describes how to assess multiple
dimensions of interest. To evaluate a text, a large language model (LLM) is
prompted with each rubric question and produces a distribution over potential
responses. The LLM predictions often fail to agree well with human judges --
indeed, the humans do not fully agree with one another. However, the multiple
LLM distributions can be \\(\textit\{combined\}\\) to \\(\textit\{predict\}\\) each human
judge's annotations on all questions, including a summary question that
assesses overall quality or relevance. LLM-Rubric accomplishes this by training
a small feed-forward neural network that includes both judge-specific and
judge-independent parameters. When evaluating dialogue systems in a human-AI
information-seeking task, we find that LLM-Rubric with 9 questions (assessing
dimensions such as naturalness, conciseness, and citation quality) predicts
human judges' assessment of overall user satisfaction, on a scale of 1--4, with
RMS error \\(< 0.5\\), a \\(2\times\\) improvement over the uncalibrated baseline.
