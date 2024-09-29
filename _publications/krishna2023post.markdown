---
layout: publication
title: Post Hoc Explanations Of Language Models Can Improve Language Models
authors: Krishna Satyapriya, Ma Jiaqi, Slack Dylan, Ghandeharioun Asma, Singh Sameer, Lakkaraju Himabindu
conference: "Arxiv"
year: 2023
bibkey: krishna2023post
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11426"}
tags: ['Interpretability And Explainability', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in performing complex tasks. Moreover recent research has shown that incorporating human45;annotated rationales (e.g. Chain45;of45;Thought prompting) during in45;context learning can significantly enhance the performance of these models particularly on tasks that require reasoning capabilities. However incorporating such rationales poses challenges in terms of scalability as this requires a high degree of human involvement. In this work we present a novel framework Amplifying Model Performance by Leveraging In45;Context Learning with Post Hoc Explanations (AMPLIFY) which addresses the aforementioned challenges by automating the process of rationale generation. To this end we leverage post hoc explanation methods which output attribution scores (explanations) capturing the influence of each of the input features on model predictions. More specifically we construct automated natural language rationales that embed insights from post hoc explanations to provide corrective signals to LLMs. Extensive experimentation with real45;world datasets demonstrates that our framework AMPLIFY leads to prediction accuracy improvements of about 1045;2537; over a wide range of tasks including those where prior approaches which rely on human45;annotated rationales such as Chain45;of45;Thought prompting fall short. Our work makes one of the first attempts at highlighting the potential of post hoc explanations as valuable tools for enhancing the effectiveness of LLMs. Furthermore we conduct additional empirical analyses and ablation studies to demonstrate the impact of each of the components of AMPLIFY which in turn leads to critical insights for refining in45;context learning.
