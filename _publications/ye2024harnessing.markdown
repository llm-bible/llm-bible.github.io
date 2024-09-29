---
layout: publication
title: Harnessing Multimodal Large Language Models For Multimodal Sequential Recommendation
authors: Ye Yuyang, Zheng Zhi, Shen Yishan, Wang Tianshu, Zhang Hengruo, Zhu Peijun, Yu Runlong, Zhang Kai, Xiong Hui
conference: "Arxiv"
year: 2024
bibkey: ye2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09698"}
tags: ['Applications', 'Fine Tuning', 'Merging', 'Multimodal Models', 'Prompting', 'RAG']
---
Recent advances in Large Language Models (LLMs) have demonstrated significant potential in the field of Recommendation Systems (RSs). Most existing studies have focused on converting user behavior logs into textual prompts and leveraging techniques such as prompt tuning to enable LLMs for recommendation tasks. Meanwhile research interest has recently grown in multimodal recommendation systems that integrate data from images text and other sources using modality fusion techniques. This introduces new challenges to the existing LLM45;based recommendation paradigm which relies solely on text modality information. Moreover although Multimodal Large Language Models (MLLMs) capable of processing multi45;modal inputs have emerged how to equip MLLMs with multi45;modal recommendation capabilities remains largely unexplored. To this end in this paper we propose the Multimodal Large Language Model45;enhanced Multimodaln Sequential Recommendation (MLLM45;MSR) model. To capture the dynamic user preference we design a two45;stage user preference summarization method. Specifically we first utilize an MLLM45;based item45;summarizer to extract image feature given an item and convert the image into text. Then we employ a recurrent user preference summarization generation paradigm to capture the dynamic changes in user preferences based on an LLM45;based user45;summarizer. Finally to enable the MLLM for multi45;modal recommendation task we propose to fine45;tune a MLLM45;based recommender using Supervised Fine45;Tuning (SFT) techniques. Extensive evaluations across various datasets validate the effectiveness of MLLM45;MSR showcasing its superior ability to capture and adapt to the evolving dynamics of user preferences.
