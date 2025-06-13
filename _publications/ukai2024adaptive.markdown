---
layout: publication
title: 'Adacoder: Adaptive Prompt Compression For Programmatic Visual Question Answering'
authors: Mahiro Ukai, Shuhei Kurita, Atsushi Hashimoto, Yoshitaka Ushiku, Nakamasa Inoue
conference: "Arxiv"
year: 2024
bibkey: ukai2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19410"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Training Techniques', 'Prompting']
---
Visual question answering aims to provide responses to natural language
questions given visual input. Recently, visual programmatic models (VPMs),
which generate executable programs to answer questions through large language
models (LLMs), have attracted research interest. However, they often require
long input prompts to provide the LLM with sufficient API usage details to
generate relevant code. To address this limitation, we propose AdaCoder, an
adaptive prompt compression framework for VPMs. AdaCoder operates in two
phases: a compression phase and an inference phase. In the compression phase,
given a preprompt that describes all API definitions in the Python language
with example snippets of code, a set of compressed preprompts is generated,
each depending on a specific question type. In the inference phase, given an
input question, AdaCoder predicts the question type and chooses the appropriate
corresponding compressed preprompt to generate code to answer the question.
Notably, AdaCoder employs a single frozen LLM and pre-defined prompts, negating
the necessity of additional training and maintaining adaptability across
different powerful black-box LLMs such as GPT and Claude. In experiments, we
apply AdaCoder to ViperGPT and demonstrate that it reduces token length by
71.1%, while maintaining or even improving the performance of visual question
answering.
