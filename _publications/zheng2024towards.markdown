---
layout: publication
title: 'Towards A Unified Paradigm: Integrating Recommendation Systems As A New Language In Large Models'
authors: Kai Zheng, Qingfeng Sun, Can Xu, Peng Yu, Qingwei Guo
conference: "Arxiv"
year: 2024
bibkey: zheng2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16933"}
tags: ['Fine-Tuning', 'Tools', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
This paper explores the use of Large Language Models (LLMs) for sequential
recommendation, which predicts users' future interactions based on their past
behavior. We introduce a new concept, "Integrating Recommendation Systems as a
New Language in Large Models" (RSLLM), which combines the strengths of
traditional recommenders and LLMs. RSLLM uses a unique prompting method that
combines ID-based item embeddings from conventional recommendation models with
textual item features. It treats users' sequential behaviors as a distinct
language and aligns the ID embeddings with the LLM's input space using a
projector. We also propose a two-stage LLM fine-tuning framework that refines a
pretrained LLM using a combination of two contrastive losses and a language
modeling loss. The LLM is first fine-tuned using text-only prompts, followed by
target domain fine-tuning with unified prompts. This trains the model to
incorporate behavioral knowledge from the traditional sequential recommender
into the LLM. Our empirical results validate the effectiveness of our proposed
framework.
