---
layout: publication
title: 'Towards Neural Synthesis For Smt-assisted Proof-oriented Programming'
authors: Chakraborty Saikat, Ebner Gabriel, Bhat Siddharth, Fakhoury Sarah, Fatima Sakina, Lahiri Shuvendu, Swamy Nikhil
conference: "Arxiv"
year: 2024
bibkey: chakraborty2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01787"}
tags: ['GPT', 'Model Architecture', 'RAG']
---
Proof-oriented programs mix computational content with proofs of program
correctness. However, the human effort involved in programming and proving is
still substantial, despite the use of Satisfiability Modulo Theories (SMT)
solvers to automate proofs in languages such as F*. Seeking to spur research on
using AI to automate the construction of proof-oriented programs, we curate a
dataset of 600K lines of open-source F* programs and proofs, including software
used in production systems ranging from Windows and Linux to Python and
Firefox. Our dataset includes around 32K top-level F* definitions, each
representing a type-directed program and proof synthesis problem producing a
definition given a formal specification expressed as an F* type. We provide a
program fragment checker that queries F* to check the correctness of candidate
solutions. We also report on an extended version of our dataset containing a
total of 940K lines of programs and proofs, with a total of 54k top-level F*
definitions. We believe this is the largest corpus of SMT-assisted program
proofs coupled with a reproducible program-fragment checker. Grounded in this
dataset, we investigate the use of AI to synthesize programs and their proofs
in F*, with promising results. Our main finding in that the performance of
fine-tuned smaller language models (such as Phi-2 or StarCoder) compare
favorably with large language models (such as GPT-4), at a much lower
computational cost. We also identify various type-based retrieval augmentation
techniques and find that they boost performance significantly. With detailed
error analysis and case studies, we identify potential strengths and weaknesses
of models and techniques and suggest directions for future improvements.
