---
layout: publication
title: Lawluo A Chinese Law Firm Co-run By LLM Agents
authors: Sun Jingyun, Dai Chengxiao, Luo Zhongze, Chang Yangbo, Li Yang
conference: "Arxiv"
year: 2024
bibkey: sun2024lawluo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16252"}
  - {name: "Code", url: "https://github.com/NEFUJing/LawLuo"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) demonstrate substantial potential in delivering legal consultation services to users without a legal background attributed to their superior text comprehension and generation capabilities. Nonetheless existing Chinese legal LLMs limit interaction to a single model-user dialogue unlike the collaborative consultations typical of law firms where multiple staff members contribute to a single consultation. This limitation prevents an authentic consultation experience. Additionally extant Chinese legal LLMs suffer from critical limitations (1) insufficient control over the quality of instruction fine-tuning data; (2) increased model hallucination resulting from users ambiguous queries; and (3) a reduction in the models ability to follow instructions over multiple dialogue turns. In response to these challenges we propose a novel legal dialogue framework that leverages the collaborative capabilities of multiple LLM agents termed LawLuo. This framework encompasses four agents a receptionist a lawyer a secretary and a boss each responsible for different functionalities collaboratively providing a comprehensive legal consultation to users. Additionally we constructed two high-quality legal dialogue datasets KINLED and MURLED and fine-tuned ChatGLM-3-6b using these datasets. We propose a legal query clarification algorithm called ToLC. Experimental results demonstrate that LawLuo outperforms baseline LLMs including GPT-4 across three dimensions lawyer-like language style the usefulness of legal advice and the accuracy of legal knowledge. Our code and datasets are available at https://github.com/NEFUJing/LawLuo.
