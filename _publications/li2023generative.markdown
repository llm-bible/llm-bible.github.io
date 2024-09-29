---
layout: publication
title: Generative Judge For Evaluating Alignment
authors: Li Junlong, Sun Shichao, Yuan Weizhe, Fan Run-ze, Zhao Hai, Liu Pengfei
conference: "Arxiv"
year: 2023
bibkey: li2023generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05470"}
  - {name: "Code", url: "https://github.com/GAIR&#45;NLP/auto&#45;j"}
tags: ['Has Code', 'Interpretability And Explainability', 'Reinforcement Learning', 'Tools']
---
The rapid development of Large Language Models (LLMs) has substantially expanded the range of tasks they can address. In the field of Natural Language Processing (NLP) researchers have shifted their focus from conventional NLP tasks (e.g. sequence tagging and parsing) towards tasks that revolve around aligning with human needs (e.g. brainstorming and email writing). This shift in task distribution imposes new requirements on evaluating these aligned models regarding generality (i.e. assessing performance across diverse scenarios) flexibility (i.e. examining under different protocols) and interpretability (i.e. scrutinizing models with explanations). In this paper we propose a generative judge with 13B parameters Auto45;J designed to address these challenges. Our model is trained on user queries and LLM45;generated responses under massive real45;world scenarios and accommodates diverse evaluation protocols (e.g. pairwise response comparison and single45;response evaluation) with well45;structured natural language critiques. To demonstrate the efficacy of our approach we construct a new testbed covering 58 different scenarios. Experimentally Auto45;J outperforms a series of strong competitors including both open45;source and closed45;source models by a large margin. We also provide detailed analysis and case studies to further reveal the potential of our method and make a variety of resources public at https://github.com/GAIR&#45;NLP/auto&#45;j.
