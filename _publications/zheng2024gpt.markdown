---
layout: publication
title: Gpt45;4v(ision) Is A Generalist Web Agent If Grounded
authors: Zheng Boyuan, Gou Boyu, Kil Jihyung, Sun Huan, Su Yu
conference: "Arxiv"
year: 2024
bibkey: zheng2024gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.01614"}
  - {name: "Code", url: "https://github.com/OSU&#45;NLP&#45;Group/SeeAct"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Tools']
---
The recent development on large multimodal models (LMMs) especially GPT45;4V(ision) and Gemini has been quickly expanding the capability boundaries of multimodal models beyond traditional tasks like image captioning and visual question answering. In this work we explore the potential of LMMs like GPT45;4V as a generalist web agent that can follow natural language instructions to complete tasks on any given website. We propose SEEACT a generalist web agent that harnesses the power of LMMs for integrated visual understanding and acting on the web. We evaluate on the recent MIND2WEB benchmark. In addition to standard offline evaluation on cached websites we enable a new online evaluation setting by developing a tool that allows running web agents on live websites. We show that GPT45;4V presents a great potential for web agents 45;45; it can successfully complete 51.1 of the tasks on live websites if we manually ground its textual plans into actions on the websites. This substantially outperforms text45;only LLMs like GPT45;4 or smaller models (FLAN45;T5 and BLIP45;2) specifically fine45;tuned for web agents. However grounding still remains a major challenge. Existing LMM grounding strategies like set45;of45;mark prompting turns out to be not effective for web agents and the best grounding strategy we develop in this paper leverages both the HTML structure and visuals. Yet there is still a substantial gap with oracle grounding leaving ample room for further improvement. All code data and evaluation tools are available at https://github.com/OSU&#45;NLP&#45;Group/SeeAct.
