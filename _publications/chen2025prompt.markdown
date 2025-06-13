---
layout: publication
title: 'Prompt Stability Matters: Evaluating And Optimizing Auto-generated Prompt In General-purpose Systems'
authors: Ke Chen, Yufei Zhou, Xitong Zhang, Haohan Wang
conference: "Arxiv"
year: 2025
bibkey: chen2025prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13546'}
tags: ['Attention Mechanism', 'Agentic', 'Interpretability and Explainability', 'Agent', 'RAG', 'Model Architecture', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Automatic prompt generation plays a crucial role in enabling general-purpose multi-agent systems to perform diverse tasks autonomously. Existing methods typically evaluate prompts based on their immediate task performance, overlooking the intrinsic qualities that determine their reliability. This outcome-centric view not only limits interpretability but also fails to account for the inherent stochasticity of large language models (LLMs). In this work, we bring attention to prompt stability-the consistency of model responses across repeated executions-as a key factor for building robust and effective prompt generation systems. To quantify this, we propose semantic stability as a criterion for assessing the response consistency of prompts, and fine-tune a LLaMA-based evaluator to measure it automatically across tasks. These components have enabled us to develop the first stability-aware general-purpose prompt generation system that leverages stability feedback to iteratively enhance both prompt quality and system-level performance. Furthermore, we establish a logical chain between prompt stability and task success by analyzing the structural dependencies within our system, proving stability as a necessary condition for effective system-level execution. Empirical results across general and domain-specific tasks demonstrate that our stability-aware framework improves both accuracy and output consistency. By shifting the focus from one-off results to persistent reliability, our work offers a new perspective on prompt design and contributes practical tools for building more trustworthy general-purpose systems.
