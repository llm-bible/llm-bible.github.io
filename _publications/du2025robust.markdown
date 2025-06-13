---
layout: publication
title: 'Boost, Disentangle, And Customize: A Robust System2-to-system1 Pipeline For Code Generation'
authors: Kounianhua Du, Hanjing Wang, Jianxing Liu, Jizheng Chen, Xinyi Dai, Yasheng Wang, Ruiming Tang, Yong Yu, Jun Wang, Weinan Zhang
conference: "Arxiv"
year: 2025
bibkey: du2025robust
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12492'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Security', 'Tools', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Pruning', 'Multimodal Models', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
various domains, particularly in system 1 tasks, yet the intricacies of their
problem-solving mechanisms in system 2 tasks are not sufficiently explored.
Recent research on System2-to-System1 methods surge, exploring the System 2
reasoning knowledge via inference-time computation and compressing the explored
knowledge into System 1 process. In this paper, we focus on code generation,
which is a representative System 2 task, and identify two primary challenges:
(1) the complex hidden reasoning processes and (2) the heterogeneous data
distributions that complicate the exploration and training of robust LLM
solvers. To tackle these issues, we propose a novel BDC framework that explores
insightful System 2 knowledge of LLMs using a MC-Tree-Of-Agents algorithm with
mutual \textbf\{B\}oosting, \textbf\{D\}isentangles the heterogeneous training data
for composable LoRA-experts, and obtain \textbf\{C\}ustomized problem solver for
each data instance with an input-aware hypernetwork to weight over the
LoRA-experts, offering effectiveness, flexibility, and robustness. This
framework leverages multiple LLMs through mutual verification and boosting,
integrated into a Monte-Carlo Tree Search process enhanced by reflection-based
pruning and refinement. Additionally, we introduce the DisenLora algorithm,
which clusters heterogeneous data to fine-tune LLMs into composable Lora
experts, enabling the adaptive generation of customized problem solvers through
an input-aware hypernetwork. This work lays the groundwork for advancing LLM
capabilities in complex reasoning tasks, offering a novel System2-to-System1
solution.
