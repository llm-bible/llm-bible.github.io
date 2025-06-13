---
layout: publication
title: 'Do Large Language Model Benchmarks Test Reliability?'
authors: Joshua Vendrow, Edward Vendrow, Sara Beery, Aleksander Madry
conference: "Arxiv"
year: 2025
bibkey: vendrow2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03461"}
  - {name: "Code", url: "https://github.com/MadryLab/platinum-benchmarks"}
tags: ['Has Code', 'Uncategorized']
---
When deploying large language models (LLMs), it is important to ensure that
these models are not only capable, but also reliable. Many benchmarks have been
created to track LLMs' growing capabilities, however there has been no similar
focus on measuring their reliability. To understand the potential ramifications
of this gap, we investigate how well current benchmarks quantify model
reliability. We find that pervasive label errors can compromise these
evaluations, obscuring lingering model failures and hiding unreliable behavior.
  Motivated by this gap in the evaluation of reliability, we then propose the
concept of so-called platinum benchmarks, i.e., benchmarks carefully curated to
minimize label errors and ambiguity. As a first attempt at constructing such
benchmarks, we revise examples from fifteen existing popular benchmarks. We
evaluate a wide range of models on these platinum benchmarks and find that,
indeed, frontier LLMs still exhibit failures on simple tasks such as
elementary-level math word problems. Analyzing these failures further reveals
previously unidentified patterns of problems on which frontier models
consistently struggle. We provide code at
https://github.com/MadryLab/platinum-benchmarks
