---
layout: publication
title: 'Synergistic Multi-agent Framework With Trajectory Learning For Knowledge-intensive Tasks'
authors: Shengbin Yue, Siyuan Wang, Wei Chen, Xuanjing Huang, Zhongyu Wei
conference: "Arxiv"
year: 2024
bibkey: yue2024synergistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09893"}
  - {name: "Code", url: "https://github.com/yueshengbin/SMART"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'RAG', 'Has Code', 'Interpretability and Explainability']
---
Recent advancements in Large Language Models (LLMs) have led to significant
breakthroughs in various natural language processing tasks. However, generating
factually consistent responses in knowledge-intensive scenarios remains a
challenge due to issues such as hallucination, difficulty in acquiring
long-tailed knowledge, and limited memory expansion. This paper introduces
SMART, a novel multi-agent framework that leverages external knowledge to
enhance the interpretability and factual consistency of LLM-generated
responses. SMART comprises four specialized agents, each performing a specific
sub-trajectory action to navigate complex knowledge-intensive tasks. We propose
a multi-agent co-training paradigm, Long-Short Trajectory Learning, which
ensures synergistic collaboration among agents while maintaining fine-grained
execution by each agent. Extensive experiments on five knowledge-intensive
tasks demonstrate SMART's superior performance compared to widely adopted
knowledge internalization and knowledge enhancement methods. Our framework can
extend beyond knowledge-intensive tasks to more complex scenarios. Our code is
available at https://github.com/yueshengbin/SMART.
