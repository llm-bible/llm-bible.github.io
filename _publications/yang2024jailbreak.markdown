---
layout: publication
title: 'Seqar: Jailbreak Llms With Sequential Auto-generated Characters'
authors: Yan Yang, Zeguan Xiao, Xin Lu, Hongru Wang, Xuetao Wei, Hailiang Huang, Guanhua Chen, Yun Chen
conference: "Arxiv"
year: 2024
bibkey: yang2024jailbreak
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.01902'}
tags: ['Security', 'GPT', 'Applications', 'Model Architecture', 'Tools', 'Prompting', 'Responsible AI']
---
The widespread applications of large language models (LLMs) have brought
about concerns regarding their potential misuse. Although aligned with human
preference data before release, LLMs remain vulnerable to various malicious
attacks. In this paper, we adopt a red-teaming strategy to enhance LLM safety
and introduce SeqAR, a simple yet effective framework to design jailbreak
prompts automatically. The SeqAR framework generates and optimizes multiple
jailbreak characters and then applies sequential jailbreak characters in a
single query to bypass the guardrails of the target LLM. Different from
previous work which relies on proprietary LLMs or seed jailbreak templates
crafted by human expertise, SeqAR can generate and optimize the jailbreak
prompt in a cold-start scenario using open-sourced LLMs without any seed
jailbreak templates. Experimental results show that SeqAR achieves attack
success rates of 88% and 60% in bypassing the safety alignment of GPT-3.5-1106
and GPT-4, respectively. Furthermore, we extensively evaluate the
transferability of the generated templates across different LLMs and held-out
malicious requests, while also exploring defense strategies against the
jailbreak attack designed by SeqAR.
