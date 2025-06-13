---
layout: publication
title: 'Dressing Up LLM: Efficient Stylized Question-answering Via Style Subspace Editing'
authors: Xinyu Ma, Yifeng Xu, Yang Lin, Tianlong Wang, Xu Chu, Xin Gao, Junfeng Zhao, Yasha Wang
conference: "Arxiv"
year: 2025
bibkey: ma2025dressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14371"}
  - {name: "Code", url: "https://github.com/ArthurLeoM/DRESS-LLM"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
We introduce DRESS, a novel approach for generating stylized large language
model (LLM) responses through representation editing. Existing methods like
prompting and fine-tuning are either insufficient for complex style adaptation
or computationally expensive, particularly in tasks like NPC creation or
character role-playing. Our approach leverages the over-parameterized nature of
LLMs to disentangle a style-relevant subspace within the model's representation
space to conduct representation editing, ensuring a minimal impact on the
original semantics. By applying adaptive editing strengths, we dynamically
adjust the steering vectors in the style subspace to maintain both stylistic
fidelity and semantic integrity. We develop two stylized QA benchmark datasets
to validate the effectiveness of DRESS, and the results demonstrate significant
improvements compared to baseline methods such as prompting and ITI. In short,
DRESS is a lightweight, train-free solution for enhancing LLMs with flexible
and effective style control, making it particularly useful for developing
stylized conversational agents. Codes and benchmark datasets are available at
https://github.com/ArthurLeoM/DRESS-LLM.
