---
layout: publication
title: Do Llms Know When To NOT Answer Investigating Abstention Abilities Of Large Language Models
authors: Madhusudhan Nishanth, Madhusudhan Sathwik Tejaswi, Yadav Vikas, Hashemi Masoud
conference: "Arxiv"
year: 2024
bibkey: madhusudhan2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16221"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
As Large Language Models (LLMs) achieve remarkable performance across various NLP tasks their reliability becomes essential for widespread adoption. This paper focuses on Abstention Ability (AA) a critical yet under explored aspect of reliability - the ability of LLMs to refrain from answering questions when they are uncertain or when definitive answer is not possible while maintaining question-answering (QA) task performance. While previous works have focused on understanding the recollection abilities of LLMs or their ability to identify imponderable/unanswerable questions we believe there is a need for an effective AA evaluation method. Therefore we propose a black-box evaluation methodology to examine and understand the AA of LLMs across a variety of multiple-choice QA tasks. We measure AA by rewarding models for abstaining from answering when their predictions are incorrect or when the questions are inherently unanswerable. We investigate three strategies Strict Prompting Verbal Confidence Thresholding and Chain-of-Thought (CoT) to understand their impact on abstention across different LLMs. Our findings reveal that while even state-of-the-art LLMs like GPT-4 struggle with abstention strategic prompting such as CoT can significantly enhance this ability. Furthermore we demonstrate that improving AA also leads to better overall QA task performance underscoring the importance of evaluating AA in LLMs.
