---
layout: publication
title: Minigpt45;4 Enhancing Vision45;language Understanding With Advanced Large Language Models
authors: Deyao Zhu, Jun Chen, Xiaoqian Shen, Xiang Li, Mohamed Elhoseiny
conference: "Arxiv"
year: 2023
bibkey: zhu2023minigpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2304.10592v2"}
  - {name: "Code", url: "https://minigpt&#45;4.github.io/"}
tags: ['Applications', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
The recent GPT45;4 has demonstrated extraordinary multi45;modal abilities such as directly generating websites from handwritten text and identifying humorous elements within images. These features are rarely observed in previous vision45;language models. However the technical details behind GPT45;4 continue to remain undisclosed. We believe that the enhanced multi45;modal generation capabilities of GPT45;4 stem from the utilization of sophisticated large language models (LLM). To examine this phenomenon we present MiniGPT45;4 which aligns a frozen visual encoder with a frozen advanced LLM Vicuna using one projection layer. Our work for the first time uncovers that properly aligning the visual features with an advanced large language model can possess numerous advanced multi45;modal abilities demonstrated by GPT45;4 such as detailed image description generation and website creation from hand45;drawn drafts. Furthermore we also observe other emerging capabilities in MiniGPT45;4 including writing stories and poems inspired by given images teaching users how to cook based on food photos and so on. In our experiment we found that the model trained on short image caption pairs could produce unnatural language outputs (e.g. repetition and fragmentation). To address this problem we curate a detailed image description dataset in the second stage to finetune the model which consequently improves the models generation reliability and overall usability. Our code pre45;trained model and collected dataset are available at https://minigpt&#45;4.github.io/.
