---
layout: publication
title: 'Reasonagain: Using Extractable Symbolic Programs To Evaluate Mathematical Reasoning'
authors: Xiaodong Yu, Ben Zhou, Hao Cheng, Dan Roth
conference: "Arxiv"
year: 2024
bibkey: yu2024using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19056"}
tags: ['RAG', 'GPT', 'Prompting', 'Model Architecture']
---
Existing math datasets evaluate the reasoning abilities of large language
models (LLMs) by either using the final answer or the intermediate reasoning
steps derived from static examples. However, the former approach fails to
surface model's uses of shortcuts and wrong reasoning while the later poses
challenges in accommodating alternative solutions. In this work, we seek to use
symbolic programs as a means for automated evaluation if a model can
consistently produce correct final answers across various inputs to the
program. We begin by extracting programs for popular math datasets (GSM8K and
MATH) using GPT4-o. For those executable programs verified using the original
input-output pairs, they are found to encapsulate the proper reasoning required
to solve the original text questions. We then prompt GPT4-o to generate new
questions using alternative input-output pairs based the extracted program. We
apply the resulting datasets to evaluate a collection of LLMs. In our
experiments, we observe significant accuracy drops using our proposed
evaluation compared with original static examples, suggesting the fragility of
math reasoning in state-of-the-art LLMs.
