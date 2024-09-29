---
layout: publication
title: Distilling Algorithmic Reasoning From Llms Via Explaining Solution Programs
authors: Li Jierui, Mooney Raymond
conference: "Arxiv"
year: 2024
bibkey: li2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08148"}
tags: ['Ethics And Bias', 'Interpretability And Explainability', 'RAG']
---
Distilling explicit chain45;of45;thought reasoning paths has emerged as an effective method for improving the reasoning abilities of large language models (LLMs) across various tasks. However when tackling complex tasks that pose significant challenges for state45;of45;the45;art models this technique often struggles to produce effective chains of thought that lead to correct answers. In this work we propose a novel approach to distill reasoning abilities from LLMs by leveraging their capacity to explain solutions. We apply our method to solving competitive45;level programming challenges. More specifically we employ an LLM to generate explanations for a set of <problem solution45;program pairs then use <problem explanation pairs to fine45;tune a smaller language model which we refer to as the Reasoner to learn algorithmic reasoning that can generate how45;to45;solve hints for unseen problems. Our experiments demonstrate that learning from explanations enables the Reasoner to more effectively guide program implementation by a Coder resulting in higher solve rates than strong chain45;of45;thought baselines on competitive45;level programming problems. It also outperforms models that learn directly from <problem solution45;program pairs. We curated an additional test set in the CodeContests format which includes 246 more recent problems posted after the models knowledge cutoff.
