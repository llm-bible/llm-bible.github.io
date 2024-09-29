---
layout: publication
title: Instruct Not Assist Llm45;based Multi45;turn Planning And Hierarchical Questioning For Socratic Code Debugging
authors: Kargupta Priyanka, Agarwal Ishika, Hakkani-tur Dilek, Han Jiawei
conference: "Arxiv"
year: 2024
bibkey: kargupta2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11709"}
  - {name: "Code", url: "http://github.com/agarwalishika/TreeInstruct"}
tags: ['Agentic', 'Ethics And Bias', 'Has Code', 'RAG', 'Reinforcement Learning']
---
Socratic questioning is an effective teaching strategy encouraging critical thinking and problem45;solving. The conversational capabilities of large language models (LLMs) show great potential for providing scalable real45;time student guidance. However current LLMs often give away solutions directly making them ineffective instructors. We tackle this issue in the code debugging domain with TreeInstruct an Instructor agent guided by a novel state space45;based planning algorithm. TreeInstruct asks probing questions to help students independently identify and resolve errors. It estimates a students conceptual and syntactical knowledge to dynamically construct a question tree based on their responses and current knowledge state effectively addressing both independent and dependent mistakes concurrently in a multi45;turn interaction setting. In addition to using an existing single45;bug debugging benchmark we construct a more challenging multi45;bug dataset of 150 coding problems incorrect solutions and bug fixes 45;45; all carefully constructed and annotated by experts. Extensive evaluation shows TreeInstructs state45;of45;the45;art performance on both datasets proving it to be a more effective instructor than baselines. Furthermore a real45;world case study with five students of varying skill levels further demonstrates TreeInstructs ability to guide students to debug their code efficiently with minimal turns and highly Socratic questioning. We provide our code and datasets at http://github.com/agarwalishika/TreeInstruct .
