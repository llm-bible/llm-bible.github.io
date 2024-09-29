---
layout: publication
title: Learning to Trust Your Feelings Leveraging Self-awareness in LLMs for Hallucination Mitigation
authors: Liang Yuxin, Song Zhuoyang, Wang Hao, Zhang Jiaxing
conference: "Arxiv"
year: 2024
bibkey: liang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15449"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We evaluate the ability of Large Language Models (LLMs) to discern and express their internal knowledge state a key factor in countering factual hallucination and ensuring reliable application of LLMs. We observe a robust self-awareness of internal knowledge state in LLMs evidenced by over 85 accuracy in knowledge probing. However LLMs often fail to express their internal knowledge during generation leading to factual hallucinations. We develop an automated hallucination annotation tool Dreamcatcher which merges knowledge probing and consistency checking methods to rank factual preference data. Using knowledge preference as reward We propose a Reinforcement Learning from Knowledge Feedback (RLKF) training framework leveraging reinforcement learning to enhance the factuality and honesty of LLMs. Our experiments across multiple models show that RLKF training effectively enhances the ability of models to utilize their internal knowledge state boosting performance in a variety of knowledge-based and honesty-related tasks.
