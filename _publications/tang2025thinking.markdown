---
layout: publication
title: 'Thinking In Character: Advancing Role-playing Agents With Role-aware Reasoning'
authors: Yihong Tang, Kehai Chen, Muyun Yang, Zhengyu Niu, Jing Li, Tiejun Zhao, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: tang2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01748"}
tags: ['Agentic', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Distillation']
---
The advancement of Large Language Models (LLMs) has spurred significant interest in Role-Playing Agents (RPAs) for applications such as emotional companionship and virtual interaction. However, recent RPAs are often built on explicit dialogue data, lacking deep, human-like internal thought processes, resulting in superficial knowledge and style expression. While Large Reasoning Models (LRMs) can be employed to simulate character thought, their direct application is hindered by attention diversion (i.e., RPAs forget their role) and style drift (i.e., overly formal and rigid reasoning rather than character-consistent reasoning). To address these challenges, this paper introduces a novel Role-Aware Reasoning (RAR) method, which consists of two important stages: Role Identity Activation (RIA) and Reasoning Style Optimization (RSO). RIA explicitly guides the model with character profiles during reasoning to counteract attention diversion, and then RSO aligns reasoning style with the character and scene via LRM distillation to mitigate style drift. Extensive experiments demonstrate that the proposed RAR significantly enhances the performance of RPAs by effectively addressing attention diversion and style drift.
