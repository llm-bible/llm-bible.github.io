---
layout: publication
title: Llmeffichecker Understanding And Testing Efficiency Degradation Of Large Language Models
authors: Feng Xiaoning, Han Xiaohong, Chen Simin, Yang Wei
conference: "Arxiv"
year: 2022
bibkey: feng2022understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03696"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Security']
---
In this paper we make the first attempt to understand and test potential computation efficiency robustness in state45;of45;the45;art LLMs. By analyzing the working mechanism and implementation of 20543 public45;accessible LLMs we observe a fundamental property in LLMs that could be manipulated in an adversarial manner to reduce computation efficiency significantly. Our key motivation is to generate test inputs that could sufficiently delay the generation of EOS such that LLMs would have to go through enough iterations to satisfy the pre45;configured threshold. We present tool which can work under both white45;box setting and black45;box setting. In the white45;box scenario tool develops a gradient45;guided technique that searches for a minimal and unnoticeable perturbation at character45;level token45;level and structure45;level. In the black45;box scenario tool employs a causal inference45;based approach to find critical tokens and similarly applies three levels of imperceptible perturbation to them. Both the white45;box and black45;box settings effectively delay the appearance of EOS compelling these inputs to reach the naturally45;unreachable threshold. To demonstrate the effectiveness of tool we conduct a systematic evaluation on nine public45;available LLMs Google T5 AllenAI WMT14 Helsinki45;NLP translator Facebook FairSeq UNICAMP45;DL translator MarianMT Google FLAN45;T5 MBZUAI LaMini45;GPT and Salesforce CodeGen. Experimental results show that tool can increase on average LLMs response latency and energy consumption by 32537; to 324437; and 34437; to 361637; respectively by perturbing just one character or token in the input sentence.
