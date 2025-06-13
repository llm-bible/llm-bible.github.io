---
layout: publication
title: 'Knowledge Editing Through Chain-of-thought'
authors: Changyue Wang, Weihang Su, Qingyao Ai, Yiqun Liu
conference: "Arxiv"
year: 2024
bibkey: wang2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17727"}
  - {name: "Code", url: "https://github.com/bebr2/EditCoT"}
tags: ['Tools', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated exceptional capabilities
across a wide range of natural language processing (NLP) tasks. However,
keeping these models up-to-date with evolving world knowledge remains a
significant challenge due to the high costs of frequent retraining. To address
this challenge, knowledge editing techniques have emerged to update LLMs with
new information without rebuilding the model from scratch. Among these, the
in-context editing paradigm stands out for its effectiveness in integrating new
knowledge while preserving the model's original capabilities. Despite its
potential, existing in-context knowledge editing methods are often
task-specific, focusing primarily on multi-hop QA tasks using structured
knowledge triples. Moreover, their reliance on few-shot prompting for task
decomposition makes them unstable and less effective in generalizing across
diverse tasks.
  In response to these limitations, we propose EditCoT, a novel knowledge
editing framework that flexibly and efficiently updates LLMs across various
tasks without retraining. EditCoT works by generating a chain-of-thought (CoT)
for a given input and then iteratively refining this CoT process using a CoT
editor based on updated knowledge. We evaluate EditCoT across a diverse range
of benchmarks, covering multiple languages and tasks. The results demonstrate
that our approach achieves state-of-the-art performance while offering superior
generalization, effectiveness, and stability compared to existing methods,
marking a significant advancement in the field of knowledge updating. Code and
data are available at: https://github.com/bebr2/EditCoT.
