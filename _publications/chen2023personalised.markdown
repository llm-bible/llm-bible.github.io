---
layout: publication
title: Personalised Distillation Empowering Open45;sourced Llms With Adaptive Learning For Code Generation
authors: Chen Hailin, Saha Amrita, Hoi Steven, Joty Shafiq
conference: "Arxiv"
year: 2023
bibkey: chen2023personalised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18628"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting']
---
With the rise of powerful closed45;sourced LLMs (ChatGPT GPT45;4) there are increasing interests in distilling the capabilies of close45;sourced LLMs to smaller open45;sourced LLMs. Previous distillation methods usually prompt ChatGPT to generate a set of instructions and answers for the student model to learn. However such standard distillation approach neglects the merits and conditions of the student model. Inspired by modern teaching principles we design a personalised distillation process in which the student attempts to solve a task first then the teacher provides an adaptive refinement for the student to improve. Instead of feeding the student with teachers prior personalised distillation enables personalised learning for the student model as it only learns on examples it makes mistakes upon and learns to improve its own solution. On code generation personalised distillation consistently outperforms standard distillation with only one third of the data. With only 2.545;3K personalised examples that incur a data45;collection cost of 445;6 we boost CodeGen45;mono45;16B by 737; to achieve 36.437; pass35;64;1 and StarCoder by 12.237; to achieve 45.837; pass35;64;1 on HumanEval.
