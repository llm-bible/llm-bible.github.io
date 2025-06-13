---
layout: publication
title: 'Llm-autodiff: Auto-differentiate Any LLM Workflow'
authors: Li Atlas Yin, Zhangyang Atlas Wang
conference: "Arxiv"
year: 2025
bibkey: yin2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.16673"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Agent', 'Few-Shot', 'Prompting']
---
Large Language Models (LLMs) have reshaped natural language processing,
powering applications from multi-hop retrieval and question answering to
autonomous agent workflows. Yet, prompt engineering -- the task of crafting
textual inputs to effectively direct LLMs -- remains difficult and
labor-intensive, particularly for complex pipelines that combine multiple LLM
calls with functional operations like retrieval and data formatting. We
introduce LLM-AutoDiff: a novel framework for Automatic Prompt Engineering
(APE) that extends textual gradient-based methods (such as Text-Grad) to
multi-component, potentially cyclic LLM architectures. Implemented within the
AdalFlow library, LLM-AutoDiff treats each textual input as a trainable
parameter and uses a frozen backward engine LLM to generate feedback-akin to
textual gradients -- that guide iterative prompt updates. Unlike prior
single-node approaches, LLM-AutoDiff inherently accommodates functional nodes,
preserves time-sequential behavior in repeated calls (e.g., multi-hop loops),
and combats the "lost-in-the-middle" problem by isolating distinct sub-prompts
(instructions, formats, or few-shot examples). It further boosts training
efficiency by focusing on error-prone samples through selective gradient
computation. Across diverse tasks, including single-step classification,
multi-hop retrieval-based QA, and agent-driven pipelines, LLM-AutoDiff
consistently outperforms existing textual gradient baselines in both accuracy
and training cost. By unifying prompt optimization through a graph-centric
lens, LLM-AutoDiff offers a powerful new paradigm for scaling and automating
LLM workflows - mirroring the transformative role that automatic
differentiation libraries have long played in neural network research.
