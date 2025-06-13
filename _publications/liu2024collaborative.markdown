---
layout: publication
title: 'Cora: Collaborative Information Perception By Large Language Model''s Weights For Recommendation'
authors: Yuting Liu, Jinghao Zhang, Yizhou Dang, Yuliang Liang, Qiang Liu, Guibing Guo, Jianzhe Zhao, Xingwei Wang
conference: "Arxiv"
year: 2024
bibkey: liu2024collaborative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10645"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Involving collaborative information in Large Language Models (LLMs) is a
promising technique for adapting LLMs for recommendation. Existing methods
achieve this by concatenating collaborative features with text tokens into a
unified sequence input and then fine-tuning to align these features with LLM's
input space. Although effective, in this work, we identify two limitations when
adapting LLMs to recommendation tasks, which hinder the integration of general
knowledge and collaborative information, resulting in sub-optimal
recommendation performance. (1) Fine-tuning LLM with recommendation data can
undermine its inherent world knowledge and fundamental competencies, which are
crucial for interpreting and inferring recommendation text. (2) Incorporating
collaborative features into textual prompts disrupts the semantics of the
original prompts, preventing LLM from generating appropriate outputs. In this
paper, we propose a new paradigm, \textbf\{Co\}llaborative \textbf\{Lo\}RA (CoRA),
with a collaborative query generator. Rather than input space alignment, this
method aligns collaborative information with LLM's parameter space,
representing them as incremental weights to update LLM's output. This way, LLM
perceives collaborative information without altering its general knowledge and
text inference capabilities. Specifically, we employ a collaborative filtering
model to extract user and item embeddings and inject them into a set number of
learnable queries. We then convert collaborative queries into collaborative
weights with low-rank properties and merge the collaborative weights into LLM's
weights, enabling LLM to perceive the collaborative signals and generate
personalized recommendations without fine-tuning or extra collaborative tokens
in prompts. Extensive experiments confirm that CoRA effectively integrates
collaborative information into LLM, enhancing recommendation performance.
