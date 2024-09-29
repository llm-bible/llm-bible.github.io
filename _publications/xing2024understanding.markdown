---
layout: publication
title: Understanding The Weakness Of Large Language Model Agents Within A Complex Android Environment
authors: Xing Mingzhe, Zhang Rongkai, Xue Hui, Chen Qi, Yang Fan, Xiao Zhen
conference: "Arxiv"
year: 2024
bibkey: xing2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06596"}
  - {name: "Code", url: "https://github.com/AndroidArenaAgent/AndroidArena"}
tags: ['Agentic', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'Reinforcement Learning', 'Security', 'Tools']
---
Large language models (LLMs) have empowered intelligent agents to execute intricate tasks within domain45;specific software such as browsers and games. However when applied to general45;purpose software systems like operating systems LLM agents face three primary challenges. Firstly the action space is vast and dynamic posing difficulties for LLM agents to maintain an up45;to45;date understanding and deliver accurate responses. Secondly real45;world tasks often require inter45;application cooperation125; demanding farsighted planning from LLM agents. Thirdly agents need to identify optimal solutions aligning with user constraints such as security concerns and preferences. These challenges motivate AndroidArena an environment and benchmark designed to evaluate LLM agents on a modern operating system. To address high45;cost of manpower we design a scalable and semi45;automated method to construct the benchmark. In the task evaluation AndroidArena incorporates accurate and adaptive metrics to address the issue of non45;unique solutions. Our findings reveal that even state45;of45;the45;art LLM agents struggle in cross45;APP scenarios and adhering to specific constraints. Additionally we identify a lack of four key capabilities i.e. understanding reasoning exploration and reflection as primary reasons for the failure of LLM agents. Furthermore we provide empirical analysis on the failure of reflection and improve the success rate by 2737; with our proposed exploration strategy. This work is the first to present valuable insights in understanding fine45;grained weakness of LLM agents and offers a path forward for future research in this area. Environment benchmark and evaluation code for AndroidArena are released at https://github.com/AndroidArenaAgent/AndroidArena.
