---
layout: publication
title: Agent-flan Designing Data And Methods Of Effective Agent Tuning For Large Language Models
authors: Chen Zehui, Liu Kuikun, Wang Qiuchen, Zhang Wenwei, Liu Jiangning, Lin Dahua, Chen Kai, Zhao Feng
conference: "Arxiv"
year: 2024
bibkey: chen2024agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12881"}
  - {name: "Code", url: "https://github.com/InternLM/Agent-FLAN"}
tags: ['Agentic', 'Has Code', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Open-sourced Large Language Models (LLMs) have achieved great success in various NLP tasks however they are still far inferior to API-based models when acting as agents. How to integrate agent ability into general LLMs becomes a crucial and urgent problem. This paper first delivers three key observations (1) the current agent training corpus is entangled with both formats following and agent reasoning which significantly shifts from the distribution of its pre-training data; (2) LLMs exhibit different learning speeds on the capabilities required by agent tasks; and (3) current approaches have side-effects when improving agent abilities by introducing hallucinations. Based on the above findings we propose Agent-FLAN to effectively Fine-tune LANguage models for Agents. Through careful decomposition and redesign of the training corpus Agent-FLAN enables Llama2-7B to outperform prior best works by 3.537; across various agent evaluation datasets. With comprehensively constructed negative samples Agent-FLAN greatly alleviates the hallucination issues based on our established evaluation benchmark. Besides it consistently improves the agent capability of LLMs when scaling model sizes while slightly enhancing the general capability of LLMs. The code will be available at https://github.com/InternLM/Agent-FLAN.
