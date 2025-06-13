---
layout: publication
title: 'Tracrbench: Generating Interpretability Testbeds With Large Language Models'
authors: Hannes Thurnherr, Jérémy Scheurer
conference: "Arxiv"
year: 2024
bibkey: thurnherr2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13714"}
tags: ['Transformer', 'GPT', 'Interpretability and Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Achieving a mechanistic understanding of transformer-based language models is
an open challenge, especially due to their large number of parameters.
Moreover, the lack of ground truth mappings between model weights and their
functional roles hinders the effective evaluation of interpretability methods,
impeding overall progress. Tracr, a method for generating compiled transformers
with inherent ground truth mappings in RASP, has been proposed to address this
issue. However, manually creating a large number of models needed for verifying
interpretability methods is labour-intensive and time-consuming. In this work,
we present a novel approach for generating interpretability test beds using
large language models (LLMs) and introduce TracrBench, a novel dataset
consisting of 121 manually written and LLM-generated, human-validated RASP
programs and their corresponding transformer weights. During this process, we
evaluate the ability of frontier LLMs to autonomously generate RASP programs
and find that this task poses significant challenges. GPT-4-turbo, with a
20-shot prompt and best-of-5 sampling, correctly implements only 57 out of 101
test programs, necessitating the manual implementation of the remaining
programs. With its 121 samples, TracrBench aims to serve as a valuable testbed
for evaluating and comparing interpretability methods.
