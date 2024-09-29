---
layout: publication
title: Psycot: Psychological Questionnaire As Powerful Chain-of-thought For Personality Detection
authors: Yang Tao, Shi Tianyuan, Wan Fanqi, Quan Xiaojun, Wang Qifan, Wu Bingzhe, Wu Jiaxiang
conference: "Arxiv"
year: 2023
bibkey: yang2023psychological
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20256"}
  - {name: "Code", url: "https://github.com/TaoYang225/PsyCoT"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security']
---
Recent advances in large language models (LLMs) such as ChatGPT have showcased remarkable zero-shot performance across various NLP tasks. However the potential of LLMs in personality detection which involves identifying an individuals personality from their written texts remains largely unexplored. Drawing inspiration from Psychological Questionnaires which are carefully designed by psychologists to evaluate individual personality traits through a series of targeted items we argue that these items can be regarded as a collection of well-structured chain-of-thought (CoT) processes. By incorporating these processes LLMs can enhance their capabilities to make more reasonable inferences on personality from textual input. In light of this we propose a novel personality detection method called PsyCoT which mimics the way individuals complete psychological questionnaires in a multi-turn dialogue manner. In particular we employ a LLM as an AI assistant with a specialization in text analysis. We prompt the assistant to rate individual items at each turn and leverage the historical rating results to derive a conclusive personality preference. Our experiments demonstrate that PsyCoT significantly improves the performance and robustness of GPT-3.5 in personality detection achieving an average F1 score improvement of 4.23/10.63 points on two benchmark datasets compared to the standard prompting method. Our code is available at https://github.com/TaoYang225/PsyCoT."
