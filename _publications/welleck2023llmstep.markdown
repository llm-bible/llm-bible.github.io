---
layout: publication
title: LLMSTEP LLM proofstep suggestions in Lean
authors: Welleck Sean, Saha Rahul
conference: "Arxiv"
year: 2023
bibkey: welleck2023llmstep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18457"}
tags: ['ARXIV', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'Tools']
---
We present LLMSTEP a tool for integrating a language model into the Lean proof assistant. LLMSTEP is a Lean 4 tactic that sends a users proof state to a server hosting a language model. The language model generates suggestions which are checked in Lean and displayed to a user in their development environment. We provide a baseline language model along with code for fine-tuning and evaluation to support further development. We provide server implementations that run on CPU a CUDA GPU or a Google Colab notebook as a step towards fast effective language model suggestions for any user.
