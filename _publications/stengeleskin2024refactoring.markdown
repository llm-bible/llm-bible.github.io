---
layout: publication
title: 'Regal: Refactoring Programs To Discover Generalizable Abstractions'
authors: Elias Stengel-eskin, Archiki Prasad, Mohit Bansal
conference: "Arxiv"
year: 2024
bibkey: stengeleskin2024refactoring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16467"}
tags: ['Model Architecture', 'GPT', 'Tools']
---
While large language models (LLMs) are increasingly being used for program
synthesis, they lack the global view needed to develop useful abstractions;
they generally predict programs one at a time, often repeating the same
functionality. Generating redundant code from scratch is both inefficient and
error-prone. To address this, we propose Refactoring for Generalizable
Abstraction Learning (ReGAL), a gradient-free method for learning a library of
reusable functions via code refactorization, i.e., restructuring code without
changing its execution output. ReGAL learns from a small set of existing
programs, iteratively verifying and refining its abstractions via execution. We
find that the shared function libraries discovered by ReGAL make programs
easier to predict across diverse domains. On five datasets -- LOGO graphics
generation, Date reasoning, TextCraft (a Minecraft-based text-game) MATH, and
TabMWP -- both open-source and proprietary LLMs improve in accuracy when
predicting programs with ReGAL functions. For CodeLlama-13B, ReGAL results in
absolute accuracy increases of 11.5% on LOGO, 26.1% on date understanding, and
8.1% on TextCraft, outperforming GPT-3.5 in two of three domains. Our analysis
reveals ReGAL's abstractions encapsulate frequently-used subroutines as well as
environment dynamics.
