---
layout: publication
title: Responsible Task Automation&#58; Empowering Large Language Models As Responsible Task Automators
authors: Zhang Zhizheng, Zhang Xiaoyi, Xie Wenxuan, Lu Yan
conference: "Arxiv"
year: 2023
bibkey: zhang2023responsible
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01242"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting', 'RAG', 'Security', 'Tools']
---
The recent success of Large Language Models (LLMs) signifies an impressive stride towards artificial general intelligence. They have shown a promising prospect in automatically completing tasks upon user instructions functioning as brain-like coordinators. The associated risks will be revealed as we delegate an increasing number of tasks to machines for automated completion. A big question emerges how can we make machines behave responsibly when helping humans automate tasks as personal copilots In this paper we explore this question in depth from the perspectives of feasibility completeness and security. In specific we present Responsible Task Automation (ResponsibleTA) as a fundamental framework to facilitate responsible collaboration between LLM-based coordinators and executors for task automation with three empowered capabilities 1) predicting the feasibility of the commands for executors; 2) verifying the completeness of executors; 3) enhancing the security (e.g. the protection of users privacy). We further propose and compare two paradigms for implementing the first two capabilities. One is to leverage the generic knowledge of LLMs themselves via prompt engineering while the other is to adopt domain-specific learnable models. Moreover we introduce a local memory mechanism for achieving the third capability. We evaluate our proposed ResponsibleTA on UI task automation and hope it could bring more attentions to ensuring LLMs more responsible in diverse scenarios.
