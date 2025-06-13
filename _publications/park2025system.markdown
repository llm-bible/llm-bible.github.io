---
layout: publication
title: '\(\textit{new News}\): System-2 Fine-tuning For Robust Integration Of New Knowledge'
authors: Core Francisco Park, Zechen Zhang, Hidenori Tanaka
conference: "Arxiv"
year: 2025
bibkey: park2025system
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01812"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods', 'Merging']
---
Humans and intelligent animals can effortlessly internalize new information
("news") and accurately extract the implications for performing downstream
tasks. While large language models (LLMs) can achieve this through in-context
learning (ICL) when the news is explicitly given as context, fine-tuning
remains challenging for the models to consolidate learning in weights. In this
paper, we introduce \\(\textit\{New News\}\\), a dataset composed of hypothetical yet
plausible news spanning multiple domains (mathematics, coding, discoveries,
leaderboards, events), accompanied by downstream evaluation questions whose
correct answers critically depend on understanding and internalizing the news.
We first demonstrate a substantial gap between naive fine-tuning and in-context
learning (FT-ICL gap) on our news dataset. To address this gap, we explore a
suite of self-play data generation protocols -- paraphrases, implications and
Self-QAs -- designed to distill the knowledge from the model with context into
the weights of the model without the context, which we term \\(\textit\{System-2
Fine-tuning\}\\) (Sys2-FT). We systematically evaluate ICL and Sys2-FT performance
across data domains and model scales with the Qwen 2.5 family of models. Our
results demonstrate that the self-QA protocol of Sys2-FT significantly improves
models' in-weight learning of the news. Furthermore, we discover the
\\(\textit\{contexual shadowing effect\}\\), where training with the news \\(\textit\{in
context\}\\) followed by its rephrases or QAs degrade learning of the news.
Finally, we show preliminary evidence of an emerging scaling law of Sys2-FT.
