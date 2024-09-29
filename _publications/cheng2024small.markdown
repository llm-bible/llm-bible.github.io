---
layout: publication
title: Small Agent Can Also Rock! Empowering Small Language Models As Hallucination Detector
authors: Cheng Xiaoxue, Li Junyi, Zhao Wayne Xin, Zhang Hongzhi, Zhang Fuzheng, Zhang Di, Gai Kun, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: cheng2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11277"}
  - {name: "Code", url: "https://github.com/RUCAIBox/HaluAgent"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools']
---
Hallucination detection is a challenging task for large language models (LLMs) and existing studies heavily rely on powerful closed45;source LLMs such as GPT45;4. In this paper we propose an autonomous LLM45;based agent framework called HaluAgent which enables relatively smaller LLMs (e.g. Baichuan245;Chat 7B) to actively select suitable tools for detecting multiple hallucination types such as text code and mathematical expression. In HaluAgent we integrate the LLM multi45;functional toolbox and design a fine45;grained three45;stage detection framework along with memory mechanism. To facilitate the effectiveness of HaluAgent we leverage existing Chinese and English datasets to synthesize detection trajectories for fine45;tuning which endows HaluAgent with the capability for bilingual hallucination detection. Extensive experiments demonstrate that only using 2K samples for tuning LLMs HaluAgent can perform hallucination detection on various types of tasks and datasets achieving performance comparable to or even higher than GPT45;4 without tool enhancements on both in45;domain and out45;of45;domain datasets. We release our dataset and code at https://github.com/RUCAIBox/HaluAgent.
