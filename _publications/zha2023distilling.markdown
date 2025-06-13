---
layout: publication
title: 'Distilling And Retrieving Generalizable Knowledge For Robot Manipulation Via Language Corrections'
authors: Lihan Zha, Yuchen Cui, Li-heng Lin, Minae Kwon, Montserrat Gonzalez Arenas, Andy Zeng, Fei Xia, Dorsa Sadigh
conference: "Arxiv"
year: 2023
bibkey: zha2023distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10678"}
  - {name: "Code", url: "https://sites.google.com/stanford.edu/droc"}
tags: ['Efficiency and Optimization', 'Has Code', 'Prompting', 'Distillation']
---
Today's robot policies exhibit subpar performance when faced with the
challenge of generalizing to novel environments. Human corrective feedback is a
crucial form of guidance to enable such generalization. However, adapting to
and learning from online human corrections is a non-trivial endeavor: not only
do robots need to remember human feedback over time to retrieve the right
information in new settings and reduce the intervention rate, but also they
would need to be able to respond to feedback that can be arbitrary corrections
about high-level human preferences to low-level adjustments to skill
parameters. In this work, we present Distillation and Retrieval of Online
Corrections (DROC), a large language model (LLM)-based system that can respond
to arbitrary forms of language feedback, distill generalizable knowledge from
corrections, and retrieve relevant past experiences based on textual and visual
similarity for improving performance in novel settings. DROC is able to respond
to a sequence of online language corrections that address failures in both
high-level task plans and low-level skill primitives. We demonstrate that DROC
effectively distills the relevant information from the sequence of online
corrections in a knowledge base and retrieves that knowledge in settings with
new task or object instances. DROC outperforms other techniques that directly
generate robot code via LLMs by using only half of the total number of
corrections needed in the first round and requires little to no corrections
after two iterations. We show further results, videos, prompts and code on
https://sites.google.com/stanford.edu/droc .
