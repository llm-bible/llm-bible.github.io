---
layout: publication
title: 'A Generative Approach To LLM Harmfulness Detection With Special Red Flag Tokens'
authors: Sophie Xhonneux, David Dobre, Mehrnaz Mofakhami, Leo Schwinn, Gauthier Gidel
conference: "Arxiv"
year: 2025
bibkey: xhonneux2025generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16366"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Most safety training methods for large language models (LLMs) based on
fine-tuning rely on dramatically changing the output distribution of the model
when faced with a harmful request, shifting it from an unsafe answer to a
refusal to respond. These methods inherently compromise model capabilities and
might make auto-regressive models vulnerable to attacks that make likely an
initial token of affirmative response. To avoid that, we propose to expand the
model's vocabulary with a special token we call red flag token (<rf>) and
propose to fine-tune the model to generate this token at any time harmful
content is generated or about to be generated. This novel safety training
method effectively augments LLMs into generative classifiers of harmfulness at
all times during the conversation. This method offers several advantages: it
enables the model to explicitly learn the concept of harmfulness while
marginally affecting the generated distribution, thus maintaining the model's
utility. It also evaluates each generated answer rather than just the input
prompt and provides a stronger defence against sampling-based attacks. In
addition, it simplifies the evaluation of the model's robustness and reduces
correlated failures when combined with a classifier. We further show an
increased robustness to long contexts, and supervised fine-tuning attacks.
