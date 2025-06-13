---
layout: publication
title: 'Generating High-precision Feedback For Programming Syntax Errors Using Large Language Models'
authors: Tung Phung, José Cambronero, Sumit Gulwani, Tobias Kohn, Rupak Majumdar, Adish Singla, Gustavo Soares
conference: "Arxiv"
year: 2023
bibkey: phung2023generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.04662"}
tags: ['Interpretability and Explainability', 'Reinforcement Learning']
---
Large language models (LLMs), such as Codex, hold great promise in enhancing
programming education by automatically generating feedback for students. We
investigate using LLMs to generate feedback for fixing syntax errors in Python
programs, a key scenario in introductory programming. More concretely, given a
student's buggy program, our goal is to generate feedback comprising a fixed
program along with a natural language explanation describing the errors/fixes,
inspired by how a human tutor would give feedback. While using LLMs is
promising, the critical challenge is to ensure high precision in the generated
feedback, which is imperative before deploying such technology in classrooms.
The main research question we study is: Can we develop LLMs-based feedback
generation techniques with a tunable precision parameter, giving educators
quality control over the feedback that students receive? To this end, we
introduce PyFiXV, our technique to generate high-precision feedback powered by
Codex. The key idea behind PyFiXV is to use a novel run-time validation
mechanism to decide whether the generated feedback is suitable for sharing with
the student; notably, this validation mechanism also provides a precision knob
to educators. We perform an extensive evaluation using two real-world datasets
of Python programs with syntax errors and show the efficacy of PyFiXV in
generating high-precision feedback.
