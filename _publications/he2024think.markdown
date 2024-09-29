---
layout: publication
title: Think-Program-reCtify 3D Situated Reasoning with Large Language Models
authors: He Qingrong, Lin Kejun, Chen Shizhe, Hu Anwen, Jin Qin
conference: "Arxiv"
year: 2024
bibkey: he2024think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14705"}
  - {name: "Code", url: "https://qingrongh.github.io/LLM-TPC/"}
tags: ['Has Code', 'Interpretability And Explainability', 'Pretraining Methods', 'RAG', 'Security', 'Tools']
---
This work addresses the 3D situated reasoning task which aims to answer questions given egocentric observations in a 3D environment. The task remains challenging as it requires comprehensive 3D perception and complex reasoning skills. End-to-end models trained on supervised data for 3D situated reasoning suffer from data scarcity and generalization ability. Inspired by the recent success of leveraging large language models (LLMs) for visual reasoning we propose LLM-TPC a novel framework that leverages the planning tool usage and reflection capabilities of LLMs through a ThinkProgram-reCtify loop. The Think phase first decomposes the compositional question into a sequence of steps and then the Program phase grounds each step to a piece of code and calls carefully designed 3D visual perception modules. Finally the Rectify phase adjusts the plan and code if the program fails to execute. Experiments and analysis on the SQA3D benchmark demonstrate the effectiveness interpretability and robustness of our method. Our code is publicly available at https://qingrongh.github.io/LLM-TPC/.
