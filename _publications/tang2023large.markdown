---
layout: publication
title: 'Medagents: Large Language Models As Collaborators For Zero-shot Medical Reasoning'
authors: Tang Xiangru, Zou Anni, Zhang Zhuosheng, Li Ziming, Zhao Yilun, Zhang Xingyao, Cohan Arman, Gerstein Mark
conference: "Arxiv"
year: 2023
bibkey: tang2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10537"}
  - {name: "Code", url: "https://github.com/gersteinlab/MedAgents"}
tags: ['Agentic', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs), despite their remarkable progress across various general domains, encounter significant barriers in medicine and healthcare. This field faces unique challenges such as domain-specific terminologies and reasoning over specialized knowledge. To address these issues, we propose MedAgents, a novel multi-disciplinary collaboration framework for the medical domain. MedAgents leverages LLM-based agents in a role-playing setting that participate in a collaborative multi-round discussion, thereby enhancing LLM proficiency and reasoning capabilities. This training-free framework encompasses five critical steps: gathering domain experts, proposing individual analyses, summarising these analyses into a report, iterating over discussions until a consensus is reached, and ultimately making a decision. Our work focuses on the zero-shot setting, which is applicable in real-world scenarios. Experimental results on nine datasets (MedQA, MedMCQA, PubMedQA, and six subtasks from MMLU) establish that our proposed MedAgents framework excels at mining and harnessing the medical expertise within LLMs, as well as extending its reasoning abilities. Our code can be found at https://github.com/gersteinlab/MedAgents.
