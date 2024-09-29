---
layout: publication
title: Benchmarking And Defending Against Indirect Prompt Injection Attacks On Large Language Models
authors: Yi Jingwei, Xie Yueqi, Zhu Bin, Kiciman Emre, Sun Guangzhong, Xie Xing, Wu Fangzhao
conference: "Arxiv"
year: 2023
bibkey: yi2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14197"}
tags: ['Applications', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
The integration of large language models (LLMs) with external content has enabled more up45;to45;date and wide45;ranging applications of LLMs such as Microsoft Copilot. However this integration has also exposed LLMs to the risk of indirect prompt injection attacks where an attacker can embed malicious instructions within external content compromising LLM output and causing responses to deviate from user expectations. To investigate this important but underexplored issue we introduce the first benchmark for indirect prompt injection attacks named BIPIA to evaluate the risk of such attacks. Based on the evaluation our work makes a key analysis of the underlying reason for the success of the attack namely the inability of LLMs to distinguish between instructions and external content and the absence of LLMs awareness to not execute instructions within external content. Building upon this analysis we develop two black45;box methods based on prompt learning and a white45;box defense method based on fine45;tuning with adversarial training accordingly. Experimental results demonstrate that black45;box defenses are highly effective in mitigating these attacks while the white45;box defense reduces the attack success rate to near45;zero levels. Overall our work systematically investigates indirect prompt injection attacks by introducing a benchmark analyzing the underlying reason for the success of the attack and developing an initial set of defenses.
