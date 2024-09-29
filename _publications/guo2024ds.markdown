---
layout: publication
title: "Ds-agent: Automated Data Science By Empowering Large Language Models With Case-based Reasoning"
authors: Guo Siyuan, Deng Cheng, Wen Ying, Chen Hechang, Chang Yi, Wang Jun
conference: "Arxiv"
year: 2024
bibkey: guo2024ds
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17453"}
  - {name: "Code", url: "https://github.com/guosyjlu/DS-Agent"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
In this work we investigate the potential of large language models (LLMs) based agents to automate data science tasks with the goal of comprehending task requirements then building and training the best-fit machine learning models. Despite their widespread success existing LLM agents are hindered by generating unreasonable experiment plans within this scenario. To this end we present DS-Agent a novel automatic framework that harnesses LLM agent and case-based reasoning (CBR). In the development stage DS-Agent follows the CBR framework to structure an automatic iteration pipeline which can flexibly capitalize on the expert knowledge from Kaggle and facilitate consistent performance improvement through the feedback mechanism. Moreover DS-Agent implements a low-resource deployment stage with a simplified CBR paradigm to adapt past successful solutions from the development stage for direct code generation significantly reducing the demand on foundational capabilities of LLMs. Empirically DS-Agent with GPT-4 achieves 10037; success rate in the development stage while attaining 3637; improvement on average one pass rate across alternative LLMs in the deployment stage. In both stages DS-Agent achieves the best rank in performance costing 1.60 and 0.13 per run with GPT-4 respectively. Our data and code are open-sourced at https://github.com/guosyjlu/DS-Agent."
