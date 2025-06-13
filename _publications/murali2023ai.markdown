---
layout: publication
title: 'Ai-assisted Code Authoring At Scale: Fine-tuning, Deploying, And Mixed Methods Evaluation'
authors: Vijayaraghavan Murali, Chandra Maddila, Imad Ahmad, Michael Bolin, Daniel Cheng, Negar Ghorbani, Renuka Fernandez, Nachiappan Nagappan, Peter C. Rigby
conference: "Arxiv"
year: 2023
bibkey: murali2023ai
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.12050'}
tags: ['Training Techniques', 'Tools', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Generative LLMs have been shown to effectively power AI-based code authoring
tools that can suggest entire statements or blocks of code during code
authoring. In this paper we present CodeCompose, an AI-assisted code authoring
tool developed and deployed at Meta internally. CodeCompose is based on the
InCoder LLM that merges generative capabilities with bi-directionality. We have
scaled up CodeCompose to serve tens of thousands of developers at Meta, across
9 programming languages and several coding surfaces. We present our experience
in making design decisions about the model and system architecture for
CodeCompose that addresses these challenges.
  To release a LLM model at this scale, we needed to first ensure that it is
sufficiently accurate. In a random sample of 20K source code files, depending
on the language, we are able to reproduce hidden lines between 40% and 58% of
the time, an improvement of 1.4x and 4.1x over a model trained only on public
data.
  We gradually rolled CodeCompose out to developers. At the time of this
writing, 16K developers have used it with 8% of their code coming directly from
CodeCompose.
  To triangulate our numerical findings, we conduct a thematic analysis on the
feedback from 70 developers. We find that 91.5% of the feedback is positive,
with the most common themes being discovering APIs, dealing with boilerplate
code, and accelerating coding. Meta continues to integrate this feedback into
CodeCompose.
