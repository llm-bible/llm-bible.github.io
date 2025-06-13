---
layout: publication
title: 'Pop Quiz! Can A Large Language Model Help With Reverse Engineering?'
authors: Hammond Pearce, Benjamin Tan, Prashanth Krishnamurthy, Farshad Khorrami, Ramesh Karri, Brendan Dolan-gavitt
conference: "Arxiv"
year: 2022
bibkey: pearce2022pop
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.01142"}
tags: ['Interpretability and Explainability', 'Tools', 'Prompting']
---
Large language models (such as OpenAI's Codex) have demonstrated impressive
zero-shot multi-task capabilities in the software domain, including code
explanation. In this work, we examine if this ability can be used to help with
reverse engineering. Specifically, we investigate prompting Codex to identify
the purpose, capabilities, and important variable names or values from code,
even when the code is produced through decompilation. Alongside an examination
of the model's responses in answering open-ended questions, we devise a
true/false quiz framework to characterize the performance of the language
model. We present an extensive quantitative analysis of the measured
performance of the language model on a set of program purpose identification
and information extraction tasks: of the 136,260 questions we posed, it
answered 72,754 correctly. A key takeaway is that while promising, LLMs are not
yet ready for zero-shot reverse engineering.
