---
layout: publication
title: 'Chain-of-probe: Examining The Necessity And Accuracy Of Cot Step-by-step'
authors: Zezhong Wang, Xingshan Zeng, Weiwen Liu, Yufei Wang, Liangyou Li, Yasheng Wang, Lifeng Shang, Xin Jiang, Qun Liu, Kam-fai Wong
conference: "Arxiv"
year: 2024
bibkey: wang2024chain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.16144'}
tags: ['Reinforcement Learning']
---
Current research found the issue of Early Answering in large language models
(LLMs), where the models already have an answer before generating the
Chain-of-Thought (CoT). This phenomenon suggests a potential lack of necessary
dependency between the predicted answer and the reasoning process.
Consequently, two important questions arise: (1) Is CoT still necessary if the
model already has an answer? (2) Can the correctness of the answer serve as
valid evidence for the correctness of CoT? To address these questions, we
propose a method, namely Chain-of-Probe (CoP), to probe changes in the mind
during the model's reasoning. The probing results show that in a significant
number of question-answer cases, CoT appears to be unnecessary, and this
necessity correlates with the simplicity of the task, defined by reasoning
steps required. Furthermore, by analyzing patterns in mind change, we examine
the correctness of the model's reasoning. Our validation reveals that many
responses, although correct in their final answer, contain errors in their
reasoning process. To this end, we propose a strategic approach based on CoP to
prioritize answers with correct reasoning among multiple candidates, thereby
bolstering the reliability of the model's reasoning.
