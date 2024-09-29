---
layout: publication
title: Sorry45;bench Systematically Evaluating Large Language Model Safety Refusal Behaviors
authors: Xie Tinghao, Qi Xiangyu, Zeng Yi, Huang Yangsibo, Sehwag Udari Madhushani, Huang Kaixuan, He Luxi, Wei Boyi, Li Dacheng, Sheng Ying, Jia Ruoxi, Li Bo, Li Kai, Chen Danqi, Henderson Peter, Mittal Prateek
conference: "Arxiv"
year: 2024
bibkey: xie2024sorry
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14598"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
Evaluating aligned large language models (LLMs) ability to recognize and reject unsafe user requests is crucial for safe policy45;compliant deployments. Existing evaluation efforts however face three limitations that we address with SORRY45;Bench our proposed benchmark. First existing methods often use coarse45;grained taxonomies of unsafe topics and are over45;representing some fine45;grained topics. For example among the ten existing datasets that we evaluated tests for refusals of self45;harm instructions are over 3x less represented than tests for fraudulent activities. SORRY45;Bench improves on this by using a fine45;grained taxonomy of 45 potentially unsafe topics and 450 class45;balanced unsafe instructions compiled through human45;in45;the45;loop methods. Second linguistic characteristics and formatting of prompts are often overlooked like different languages dialects and more 45;45; which are only implicitly considered in many evaluations. We supplement SORRY45;Bench with 20 diverse linguistic augmentations to systematically examine these effects. Third existing evaluations rely on large LLMs (e.g. GPT45;4) for evaluation which can be computationally expensive. We investigate design choices for creating a fast accurate automated safety evaluator. By collecting 7K+ human annotations and conducting a meta45;evaluation of diverse LLM45;as45;a45;judge designs we show that fine45;tuned 7B LLMs can achieve accuracy comparable to GPT45;4 scale LLMs with lower computational cost. Putting these together we evaluate over 40 proprietary and open45;source LLMs on SORRY45;Bench analyzing their distinctive refusal behaviors. We hope our effort provides a building block for systematic evaluations of LLMs safety refusal capabilities in a balanced granular and efficient manner.
