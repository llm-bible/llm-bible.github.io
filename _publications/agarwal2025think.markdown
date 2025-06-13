---
layout: publication
title: 'Think Inside The JSON: Reinforcement Strategy For Strict LLM Schema Adherence'
authors: Bhavik Agarwal, Ishan Joshi, Viktoria Rojkova
conference: "Arxiv"
year: 2025
bibkey: agarwal2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14905"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
In this paper, we address the challenge of enforcing strict schema adherence
in large language model (LLM) generation by leveraging LLM reasoning
capabilities. Building on the DeepSeek R1 reinforcement learning framework, our
approach trains structured reasoning skills of a 1.5B parameter model through a
novel pipeline that combines synthetic reasoning dataset construction with
custom reward functions under Group Relative Policy Optimization (GRPO).
Specifically, we first perform R1 reinforcement learning on a 20K sample
unstructured-to-structured dataset, mirroring the original DeepSeek R1 methods,
to establish core reasoning abilities. Subsequently, we performed supervised
fine-tuning on a separate 10K reasoning sample dataset, focusing on refining
schema adherence for downstream tasks. Despite the relatively modest training
scope, requiring approximately 20 hours on an 8xH100 GPU cluster for GRPO
training and 3 hours on 1xA100 for SFT, our model demonstrates robust
performance in enforcing schema consistency. We compare our ThinkJSON approach
against the original DeepSeek R1 (671B), distilled versions of DeepSeek R1
(Qwen-1.5B and Qwen-7B), and Gemini 2.0 Flash (70B), showcasing its
effectiveness in real-world applications. Our results underscore the practical
utility of a resource-efficient framework for schema-constrained text
generation.
