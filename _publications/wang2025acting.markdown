---
layout: publication
title: 'Acting Less Is Reasoning More! Teaching Model To Act Efficiently'
authors: Hongru Wang, Cheng Qian, Wanjun Zhong, Xiusi Chen, Jiahao Qiu, Shijue Huang, Bowen Jin, Mengdi Wang, Kam-fai Wong, Heng Ji
conference: "Arxiv"
year: 2025
bibkey: wang2025acting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14870"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
Tool-integrated reasoning (TIR) augments large language models (LLMs) with the ability to invoke external tools during long-form reasoning, such as search engines and code interpreters, to solve tasks beyond the capabilities of internal reasoning. While reinforcement learning (RL) has shown promise in training such agents, most of existing approaches typically optimize only for final correctness without considering the efficiency or necessity of external tool use. This often leads to excessive tool calling, incurring high computational costs and hindering the development of internal reasoning capabilities - a phenomenon known as \textit\{cognitive offloading\}. To this end, we propose Optimal Tool Call-controlled Policy Optimization (OTC-PO), a simple yet effective RL-based framework that encourages models to produce accurate answers with minimal tool calls. Our method introduces a tool-integrated reward that jointly considers answer correctness and corresponding tool use behavior of model to reach that answer. To validate the effectiveness, we introduce the metric of \textit\{tool productivity\}, defined as the ratio between the number of correct answers and the total number of tool calls across all test cases. This metric reflects how efficiently tool usage contributes to successful task completion, with higher values indicating smarter and more autonomous reasoning. We instantiate this framework within both Proximal Policy Optimization (PPO) and Group Relative Preference Optimization (GRPO), resulting in OTC-PPO and OTC-GRPO. Experiments with Qwen-2.5 and Qwen-Math across multiple QA benchmarks show that our approach reduces tool calls by up to 68.3% and improves tool productivity by up to 215.4%, while maintaining comparable answer accuracy.
