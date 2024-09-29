---
layout: publication
title: 'Assistgpt: A General Multi-modal Assistant That Can Plan, Execute, Inspect, And Learn'
authors: Gao Difei, Ji Lei, Zhou Luowei, Lin Kevin Qinghong, Chen Joya, Fan Zihan, Shou Mike Zheng
conference: "Arxiv"
year: 2023
bibkey: gao2023general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.08640"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Recent research on Large Language Models (LLMs) has led to remarkable advancements in general NLP AI assistants. Some studies have further explored the use of LLMs for planning and invoking models or APIs to address more general multi-modal user queries. Despite this progress complex visual-based tasks still remain challenging due to the diverse nature of visual tasks. This diversity is reflected in two aspects 1) Reasoning paths. For many real-life applications it is hard to accurately decompose a query simply by examining the query itself. Planning based on the specific visual content and the results of each step is usually required. 2) Flexible inputs and intermediate results. Input forms could be flexible for in-the-wild cases and involves not only a single image or video but a mixture of videos and images e.g. a user-view image with some reference videos. Besides a complex reasoning process will also generate diverse multimodal intermediate results e.g. video narrations segmented video clips etc. To address such general cases we propose a multi-modal AI assistant AssistGPT with an interleaved code and language reasoning approach called Plan Execute Inspect and Learn (PEIL) to integrate LLMs with various tools. Specifically the Planner is capable of using natural language to plan which tool in Executor should do next based on the current reasoning progress. Inspector is an efficient memory manager to assist the Planner to feed proper visual information into a specific tool. Finally since the entire reasoning process is complex and flexible a Learner is designed to enable the model to autonomously explore and discover the optimal solution. We conducted experiments on A-OKVQA and NExT-QA benchmarks achieving state-of-the-art results. Moreover showcases demonstrate the ability of our system to handle questions far more complex than those found in the benchmarks.
