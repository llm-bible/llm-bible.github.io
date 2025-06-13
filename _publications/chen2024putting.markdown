---
layout: publication
title: 'Putting People In Llms'' Shoes: Generating Better Answers Via Question Rewriter'
authors: Junhao Chen, Bowen Wang, Zhouqiang Jiang, Yuta Nakashima
conference: "Arxiv"
year: 2024
bibkey: chen2024putting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10573"}
  - {name: "Code", url: "https://github.com/3244we/Question-Rewriter"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Has Code', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have demonstrated significant capabilities,
particularly in the domain of question answering (QA). However, their
effectiveness in QA is often undermined by the vagueness of user questions. To
address this issue, we introduce single-round instance-level prompt
optimization, referred to as question rewriter. By enhancing the
intelligibility of human questions for black-box LLMs, our question rewriter
improves the quality of generated answers. The rewriter is optimized using
direct preference optimization based on feedback collected from automatic
criteria for evaluating generated answers; therefore, its training does not
require costly human annotations. The experiments across multiple black-box
LLMs and long-form question answering (LFQA) datasets demonstrate the efficacy
of our method. This paper provides a practical framework for training question
rewriters and sets a precedent for future explorations in prompt optimization
within LFQA tasks. Code is available at
https://github.com/3244we/Question-Rewriter.
