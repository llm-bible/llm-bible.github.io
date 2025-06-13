---
layout: publication
title: 'An Empirical Study Of Conformal Prediction In LLM With ASP Scaffolds For Robust Reasoning'
authors: Navdeep Kaur, Lachlan Mcpheat, Alessandra Russo, Anthony G Cohn, Pranava Madhyastha
conference: "Arxiv"
year: 2025
bibkey: kaur2025empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05439"}
tags: ['Uncategorized']
---
In this paper, we examine the use of Conformal Language Modelling (CLM)
alongside Answer Set Programming (ASP) to enhance the performance of standard
open-weight LLMs on complex multi-step reasoning tasks. Using the StepGame
dataset, which requires spatial reasoning, we apply CLM to generate sets of ASP
programs from an LLM, providing statistical guarantees on the correctness of
the outputs. Experimental results show that CLM significantly outperforms
baseline models that use standard sampling methods, achieving substantial
accuracy improvements across different levels of reasoning complexity.
Additionally, the LLM-as-Judge metric enhances CLM's performance, especially in
assessing structurally and logically correct ASP outputs. However, calibrating
CLM with diverse calibration sets did not improve generalizability for tasks
requiring much longer reasoning steps, indicating limitations in handling more
complex tasks.
