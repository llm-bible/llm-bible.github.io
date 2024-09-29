---
layout: publication
title: TREACLE Thrifty Reasoning Via Context45;aware LLM And Prompt Selection
authors: Zhang Xuechen, Huang Zijian, Taga Ege Onur, Joe-wong Carlee, Oymak Samet, Chen Jiasi
conference: "Arxiv"
year: 2024
bibkey: zhang2024thrifty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13082"}
tags: ['Agentic', 'Prompting', 'Reinforcement Learning']
---
Recent successes in natural language processing have led to the proliferation of large language models (LLMs) by multiple providers. Each LLM offering has different inference accuracy monetary cost and latency and their accuracy further depends on the exact wording of the question (i.e. the specific prompt). At the same time users often have a limit on monetary budget and latency to answer all their questions and they do not know which LLMs to choose for each question to meet their accuracy and long45;term budget requirements. To navigate this rich design space we propose TREACLE (Thrifty Reasoning via Context45;Aware LLM and Prompt Selection) a reinforcement learning policy that jointly selects the model and prompting scheme while respecting the users monetary cost and latency constraints. TREACLE uses the problem context including question text embeddings (reflecting the type or difficulty of a query) and the response history (reflecting the consistency of previous responses) to make smart decisions. Our evaluations on standard reasoning datasets (GSM8K CSQA and LLC ) with various LLMs and prompts show that TREACLE enables cost savings of up to 8537; compared to baselines while maintaining high accuracy. Importantly it provides the user with the ability to gracefully trade off accuracy for cost.
