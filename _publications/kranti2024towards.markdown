---
layout: publication
title: 'Towards No-code Programming Of Cobots: Experiments With Code Synthesis By Large Code Models For Conversational Programming'
authors: Chalamalasetti Kranti, Sherzod Hakimov, David Schlangen
conference: "Arxiv"
year: 2024
bibkey: kranti2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11041'}
tags: ['Prompting', 'In-Context Learning', 'Applications']
---
While there has been a lot of research recently on robots in household
environments, at the present time, most robots in existence can be found on
shop floors, and most interactions between humans and robots happen there.
``Collaborative robots'' (cobots) designed to work alongside humans on assembly
lines traditionally require expert programming, limiting ability to make
changes, or manual guidance, limiting expressivity of the resulting programs.
To address these limitations, we explore using Large Language Models (LLMs),
and in particular, their abilities of doing in-context learning, for
conversational code generation. As a first step, we define RATS, the
``Repetitive Assembly Task'', a 2D building task designed to lay the foundation
for simulating industry assembly scenarios. In this task, a `programmer'
instructs a cobot, using natural language, on how a certain assembly is to be
built; that is, the programmer induces a program, through natural language. We
create a dataset that pairs target structures with various example instructions
(human-authored, template-based, and model-generated) and example code. With
this, we systematically evaluate the capabilities of state-of-the-art LLMs for
synthesising this kind of code, given in-context examples. Evaluating in a
simulated environment, we find that LLMs are capable of generating accurate
`first order code' (instruction sequences), but have problems producing
`higher-order code' (abstractions such as functions, or use of loops).
