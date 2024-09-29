---
layout: publication
title: Knowing What Llms DO NOT Know A Simple Yet Effective Self45;detection Method
authors: Zhao Yukun, Yan Lingyong, Sun Weiwei, Xing Guoliang, Meng Chong, Wang Shuaiqiang, Cheng Zhicong, Ren Zhaochun, Yin Dawei
conference: "Arxiv"
year: 2023
bibkey: zhao2023knowing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17918"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) have shown great potential in Natural Language Processing (NLP) tasks. However recent literature reveals that LLMs generate nonfactual responses intermittently which impedes the LLMs reliability for further utilization. In this paper we propose a novel self45;detection method to detect which questions that a LLM does not know that are prone to generate nonfactual results. Specifically we first diversify the textual expressions for a given question and collect the corresponding answers. Then we examine the divergencies between the generated answers to identify the questions that the model may generate falsehoods. All of the above steps can be accomplished by prompting the LLMs themselves without referring to any other external resources. We conduct comprehensive experiments and demonstrate the effectiveness of our method on recently released LLMs e.g. Vicuna ChatGPT and GPT45;4.
