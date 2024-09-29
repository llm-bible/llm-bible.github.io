---
layout: publication
title: On Generative Agents In Recommendation
authors: An Zhang, Yuxin Chen, Leheng Sheng, Xiang Wang, Tat-seng Chua
conference: "Arxiv"
year: 2023
bibkey: zhang2023generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2310.10108v2"}
  - {name: "Code", url: "https://github.com/LehengTHU/Agent4Rec"}
tags: ['Agentic', 'Ethics And Bias', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools']
---
Recommender systems are the cornerstone of todays information dissemination yet a disconnect between offline metrics and online performance greatly hinders their development. Addressing this challenge we envision a recommendation simulator capitalizing on recent breakthroughs in human45;level intelligence exhibited by Large Language Models (LLMs). We propose Agent4Rec a user simulator in recommendation leveraging LLM45;empowered generative agents equipped with user profile memory and actions modules specifically tailored for the recommender system. In particular these agents profile modules are initialized using real45;world datasets (e.g. MovieLens Steam Amazon45;Book) capturing users unique tastes and social traits; memory modules log both factual and emotional memories and are integrated with an emotion45;driven reflection mechanism; action modules support a wide variety of behaviors spanning both taste45;driven and emotion45;driven actions. Each agent interacts with personalized recommender models in a page45;by45;page manner relying on a pre45;implemented collaborative filtering45;based recommendation algorithm. We delve into both the capabilities and limitations of Agent4Rec aiming to explore an essential research question To what extent can LLM45;empowered generative agents faithfully simulate the behavior of real autonomous humans in recommender systems Extensive and multi45;faceted evaluations of Agent4Rec highlight both the alignment and deviation between agents and user45;personalized preferences. Beyond mere performance comparison we explore insightful experiments such as emulating the filter bubble effect and discovering the underlying causal relationships in recommendation tasks. Our codes are available at https://github.com/LehengTHU/Agent4Rec.
