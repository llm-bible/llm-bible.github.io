---
layout: publication
title: Videodirectorgpt Consistent Multi45;scene Video Generation Via Llm45;guided Planning
authors: Lin Han, Zala Abhay, Cho Jaemin, Bansal Mohit
conference: "Arxiv"
year: 2023
bibkey: lin2023consistent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15091"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Recent text45;to45;video (T2V) generation methods have seen significant advancements. However the majority of these works focus on producing short video clips of a single event (i.e. single45;scene videos). Meanwhile recent large language models (LLMs) have demonstrated their capability in generating layouts and programs to control downstream visual modules. This prompts an important question can we leverage the knowledge embedded in these LLMs for temporally consistent long video generation In this paper we propose VideoDirectorGPT a novel framework for consistent multi45;scene video generation that uses the knowledge of LLMs for video content planning and grounded video generation. Specifically given a single text prompt we first ask our video planner LLM (GPT45;4) to expand it into a video plan which includes the scene descriptions the entities with their respective layouts the background for each scene and consistency groupings of the entities. Next guided by this video plan our video generator named Layout2Vid has explicit control over spatial layouts and can maintain temporal consistency of entities across multiple scenes while being trained only with image45;level annotations. Our experiments demonstrate that our proposed VideoDirectorGPT framework substantially improves layout and movement control in both single45; and multi45;scene video generation and can generate multi45;scene videos with consistency while achieving competitive performance with SOTAs in open45;domain single45;scene T2V generation. Detailed ablation studies including dynamic adjustment of layout control strength with an LLM and video generation with user45;provided images confirm the effectiveness of each component of our framework and its future potential.
