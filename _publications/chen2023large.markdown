---
layout: publication
title: Large Language Models Are Visual Reasoning Coordinators
authors: Chen Liangyu, Li Bo, Shen Sheng, Yang Jingkang, Li Chunyuan, Keutzer Kurt, Darrell Trevor, Liu Ziwei
conference: "Arxiv"
year: 2023
bibkey: chen2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15166"}
tags: ['Applications', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Visual reasoning requires multimodal perception and commonsense cognition of the world. Recently multiple vision45;language models (VLMs) have been proposed with excellent commonsense reasoning ability in various domains. However how to harness the collective power of these complementary VLMs is rarely explored. Existing methods like ensemble still struggle to aggregate these models with the desired higher45;order communications. In this work we propose Cola a novel paradigm that coordinates multiple VLMs for visual reasoning. Our key insight is that a large language model (LLM) can efficiently coordinate multiple VLMs by facilitating natural language communication that leverages their distinct and complementary capabilities. Extensive experiments demonstrate that our instruction tuning variant Cola45;FT achieves state45;of45;the45;art performance on visual question answering (VQA) outside knowledge VQA visual entailment and visual spatial reasoning tasks. Moreover we show that our in45;context learning variant Cola45;Zero exhibits competitive performance in zero and few45;shot settings without finetuning. Through systematic ablation studies and visualizations we validate that a coordinator LLM indeed comprehends the instruction prompts as well as the separate functionalities of VLMs; it then coordinates them to enable impressive visual reasoning capabilities.
