---
layout: publication
title: Pairing Analogy-augmented Generation With Procedural Memory For Procedural QA
authors: Roth K, Gupta Rushil, Halle Simon, Liu Bang
conference: "Arxiv"
year: 2024
bibkey: roth2024pairing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01344"}
tags: ['Applications', 'Few Shot', 'RAG']
---
While LLMs in the RAG paradigm have shown remarkable performance on a variety of tasks they still under-perform on unseen domains especially on complex tasks like procedural question answering. In this work we introduce a novel formalism and structure for manipulating text-based procedures. Based on this formalism we further present a novel dataset called LCStep scraped from the LangChain Python docs. Moreover we extend the traditional RAG system to propose a novel system called analogy-augmented generation (AAG) that draws inspiration from human analogical reasoning and ability to assimilate past experiences to solve unseen problems. The proposed method uses a frozen language model with a custom procedure memory store to adapt to specialized knowledge. We demonstrate that AAG outperforms few-shot and RAG baselines on LCStep RecipeNLG and CHAMP datasets under a pairwise LLM-based evaluation corroborated by human evaluation in the case of RecipeNLG.
