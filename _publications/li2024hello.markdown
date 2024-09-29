---
layout: publication
title: "Hello Again! Llm-powered Personalized Agent For Long-term Dialogue"
authors: Li Hao, Yang Chenghao, Zhang An, Deng Yang, Wang Xiang, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: li2024hello
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05925"}
  - {name: "Code", url: "https://github.com/leolee99/LD-Agent"}
tags: ['Agentic', 'Applications', 'Has Code', 'Reinforcement Learning', 'Tools']
---
Open-domain dialogue systems have seen remarkable advancements with the development of large language models (LLMs). Nonetheless most existing dialogue systems predominantly focus on brief single-session interactions neglecting the real-world demands for long-term companionship and personalized interactions with chatbots. Crucial to addressing this real-world need are event summary and persona management which enable reasoning for appropriate long-term dialogue responses. Recent progress in the human-like cognitive and reasoning capabilities of LLMs suggests that LLM-based agents could significantly enhance automated perception decision-making and problem-solving. In response to this potential we introduce a model-agnostic framework the Long-term Dialogue Agent (LD-Agent) which incorporates three independently tunable modules dedicated to event perception persona extraction and response generation. For the event memory module long and short-term memory banks are employed to separately focus on historical and ongoing sessions while a topic-based retrieval mechanism is introduced to enhance the accuracy of memory retrieval. Furthermore the persona module conducts dynamic persona modeling for both users and agents. The integration of retrieved memories and extracted personas is subsequently fed into the generator to induce appropriate responses. The effectiveness generality and cross-domain capabilities of LD-Agent are empirically demonstrated across various illustrative benchmarks models and tasks. The code is released at https://github.com/leolee99/LD-Agent."
