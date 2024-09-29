---
layout: publication
title: Hiagent Hierarchical Working Memory Management For Solving Long45;horizon Agent Tasks With Large Language Model
authors: Hu Mengkang, Chen Tianxing, Chen Qiguang, Mu Yao, Shao Wenqi, Luo Ping
conference: "Arxiv"
year: 2024
bibkey: hu2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09559"}
  - {name: "Code", url: "https://github.com/HiAgent2024/HiAgent"}
tags: ['Agentic', 'Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Security', 'Tools']
---
Large Language Model (LLM)45;based agents exhibit significant potential across various domains operating as interactive systems that process environmental observations to generate executable actions for target tasks. The effectiveness of these agents is significantly influenced by their memory mechanism which records historical experiences as sequences of action45;observation pairs. We categorize memory into two types cross45;trial memory accumulated across multiple attempts and in45;trial memory (working memory) accumulated within a single attempt. While considerable research has optimized performance through cross45;trial memory the enhancement of agent performance through improved working memory utilization remains underexplored. Instead existing approaches often involve directly inputting entire historical action45;observation pairs into LLMs leading to redundancy in long45;horizon tasks. Inspired by human problem45;solving strategies this paper introduces HiAgent a framework that leverages subgoals as memory chunks to manage the working memory of LLM45;based agents hierarchically. Specifically HiAgent prompts LLMs to formulate subgoals before generating executable actions and enables LLMs to decide proactively to replace previous subgoals with summarized observations retaining only the action45;observation pairs relevant to the current subgoal. Experimental results across five long45;horizon tasks demonstrate that HiAgent achieves a twofold increase in success rate and reduces the average number of steps required by 3.8. Additionally our analysis shows that HiAgent consistently improves performance across various steps highlighting its robustness and generalizability. Project Page https://github.com/HiAgent2024/HiAgent .
