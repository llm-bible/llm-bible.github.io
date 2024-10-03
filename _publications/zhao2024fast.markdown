---
layout: publication
title: 'Diffagent: Fast And Accurate Text-to-image API Selection With Large Language Model'
authors: Zhao Lirui, Yang Yue, Zhang Kaipeng, Shao Wenqi, Zhang Yuxin, Qiao Yu, Luo Ping, Ji Rongrong
conference: "Arxiv"
year: 2024
bibkey: zhao2024fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01342"}
  - {name: "Code", url: "https://github.com/OpenGVLab/DiffAgent"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Text-to-image (T2I) generative models have attracted significant attention and found extensive applications within and beyond academic research. For example, the Civitai community, a platform for T2I innovation, currently hosts an impressive array of 74,492 distinct models. However, this diversity presents a formidable challenge in selecting the most appropriate model and parameters, a process that typically requires numerous trials. Drawing inspiration from the tool usage research of large language models (LLMs), we introduce DiffAgent, an LLM agent designed to screen the accurate selection in seconds via API calls. DiffAgent leverages a novel two-stage training framework, SFTA, enabling it to accurately align T2I API responses with user input in accordance with human preferences. To train and evaluate DiffAgent's capabilities, we present DABench, a comprehensive dataset encompassing an extensive range of T2I APIs from the community. Our evaluations reveal that DiffAgent not only excels in identifying the appropriate T2I API but also underscores the effectiveness of the SFTA training framework. Codes are available at https://github.com/OpenGVLab/DiffAgent.
