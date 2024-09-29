---
layout: publication
title: "Llmeffichecker: Understanding And Testing Efficiency Degradation Of Large Language Models"
authors: Feng Xiaoning, Han Xiaohong, Chen Simin, Yang Wei
conference: "Arxiv"
year: 2022
bibkey: feng2022understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03696"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Security']
---
In this paper we make the first attempt to understand and test potential computation efficiency robustness in state-of-the-art LLMs. By analyzing the working mechanism and implementation of 20543 public-accessible LLMs we observe a fundamental property in LLMs that could be manipulated in an adversarial manner to reduce computation efficiency significantly. Our key motivation is to generate test inputs that could sufficiently delay the generation of EOS such that LLMs would have to go through enough iterations to satisfy the pre-configured threshold. We present (tool) which can work under both white-box setting and black-box setting. In the white-box scenario (tool) develops a gradient-guided technique that searches for a minimal and unnoticeable perturbation at character-level token-level and structure-level. In the black-box scenario (tool) employs a causal inference-based approach to find critical tokens and similarly applies three levels of imperceptible perturbation to them. Both the white-box and black-box settings effectively delay the appearance of EOS compelling these inputs to reach the naturally-unreachable threshold. To demonstrate the effectiveness of (tool) we conduct a systematic evaluation on nine public-available LLMs Google T5 AllenAI WMT14 Helsinki-NLP translator Facebook FairSeq UNICAMP-DL translator MarianMT Google FLAN-T5 MBZUAI LaMini-GPT and Salesforce CodeGen. Experimental results show that (tool) can increase on average LLMs response latency and energy consumption by 32537; to 324437; and 34437; to 361637; respectively by perturbing just one character or token in the input sentence.
