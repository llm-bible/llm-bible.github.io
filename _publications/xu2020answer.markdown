---
layout: publication
title: 'Answer-driven Visual State Estimator For Goal-oriented Visual Dialogue'
authors: Zipeng Xu, Fangxiang Feng, Xiaojie Wang, Yushu Yang, Huixing Jiang, Zhongyuan Wang
conference: "Arxiv"
year: 2020
bibkey: xu2020answer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.00361"}
tags: ['Agentic', 'Model Architecture', 'Merging', 'ACL', 'Attention Mechanism']
---
A goal-oriented visual dialogue involves multi-turn interactions between two
agents, Questioner and Oracle. During which, the answer given by Oracle is of
great significance, as it provides golden response to what Questioner concerns.
Based on the answer, Questioner updates its belief on target visual content and
further raises another question. Notably, different answers drive into
different visual beliefs and future questions. However, existing methods always
indiscriminately encode answers after much longer questions, resulting in a
weak utilization of answers. In this paper, we propose an Answer-Driven Visual
State Estimator (ADVSE) to impose the effects of different answers on visual
states. First, we propose an Answer-Driven Focusing Attention (ADFA) to capture
the answer-driven effect on visual attention by sharpening question-related
attention and adjusting it by answer-based logical operation at each turn. Then
based on the focusing attention, we get the visual state estimation by
Conditional Visual Information Fusion (CVIF), where overall information and
difference information are fused conditioning on the question-answer state. We
evaluate the proposed ADVSE to both question generator and guesser tasks on the
large-scale GuessWhat?! dataset and achieve the state-of-the-art performances
on both tasks. The qualitative results indicate that the ADVSE boosts the agent
to generate highly efficient questions and obtains reliable visual attentions
during the reasonable question generation and guess processes.
