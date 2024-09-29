---
layout: publication
title: 'Coarse-tuning Models Of Code With Reinforcement Learning Feedback'
authors: Jain Abhinav, Adiole Chima, Chaudhuri Swarat, Reps Thomas, Jermaine Chris
conference: "Arxiv"
year: 2023
bibkey: jain2023coarse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18341"}
tags: ['Agentic', 'Reinforcement Learning']
---
Large Language Models (LLMs) pre-trained on code have recently emerged as the dominant approach to program synthesis. However these models are trained using next-token prediction which ignores the syntax and semantics of code. We propose RLCF that further trains a pre-trained LLM via reinforcement learning using feedback from a grounding function that scores the quality of the code. The grounding function uses (i) compiler-derived feedback on whether the code it generates passes a set of correctness checks; and (ii) feedback from a different LLM that compares the generated code to a reference code. RLCF is model- and language-agnostic. We empirically evaluate it on the MBJP and MathQA tasks for Java. Our experiments show that RLCF raises the odds that an LLM-generated program compiles is executable and produces the right output on tests often allowing LLMs to match the performance of 2x-8x larger LLMs.
