---
layout: publication
title: Small Language Models Fine45;tuned To Coordinate Larger Language Models Improve Complex Reasoning
authors: Juneja Gurusha, Dutta Subhabrata, Chakrabarti Soumen, Manchanda Sunny, Chakraborty Tanmoy
conference: "Arxiv"
year: 2023
bibkey: juneja2023small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18338"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) prompted to generate chain45;of45;thought (CoT) exhibit impressive reasoning capabilities. Recent attempts at prompt decomposition toward solving complex multi45;step reasoning problems depend on the ability of the LLM to simultaneously decompose and solve the problem. A significant disadvantage is that foundational LLMs are typically not available for fine45;tuning making adaptation computationally prohibitive. We believe (and demonstrate) that problem decomposition and solution generation are distinct capabilites better addressed in separate modules than by one monolithic LLM. We introduce DaSLaM which uses a decomposition generator to decompose complex problems into subproblems that require fewer reasoning steps. These subproblems are answered by a solver. We use a relatively small (13B parameters) LM as the decomposition generator which we train using policy gradient optimization to interact with a solver LM (regarded as black45;box) and guide it through subproblems thereby rendering our method solver45;agnostic. Evaluation on multiple different reasoning datasets reveal that with our method a 175 billion parameter LM (text45;davinci45;003) can produce competitive or even better performance compared to its orders45;of45;magnitude larger successor GPT45;4. Additionally we show that DaSLaM is not limited by the solvers capabilities as a function of scale; e.g. solver LMs with diverse sizes give significant performance improvement with our solver45;agnostic decomposition technique. Exhaustive ablation studies evince the superiority of our modular finetuning technique over exorbitantly large decomposer LLMs based on prompting alone.
