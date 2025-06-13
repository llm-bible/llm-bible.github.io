---
layout: publication
title: 'Atoxia: Red-teaming Large Language Models With Target Toxic Answers'
authors: Yuhao Du, Zhuo Li, Pengyu Cheng, Xiang Wan, Anningzhe Gao
conference: "Arxiv"
year: 2024
bibkey: du2024red
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14853"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Despite the substantial advancements in artificial intelligence, large
language models (LLMs) remain being challenged by generation safety. With
adversarial jailbreaking prompts, one can effortlessly induce LLMs to output
harmful content, causing unexpected negative social impacts. This vulnerability
highlights the necessity for robust LLM red-teaming strategies to identify and
mitigate such risks before large-scale application. To detect specific types of
risks, we propose a novel red-teaming method that \\(\textbf\{A\}\\)ttacks LLMs with
\\(\textbf\{T\}\\)arget \\(\textbf\{Toxi\}\\)c \\(\textbf\{A\}\\)nswers (\\(\textbf\{Atoxia\}\\)).
Given a particular harmful answer, Atoxia generates a corresponding user query
and a misleading answer opening to examine the internal defects of a given LLM.
The proposed attacker is trained within a reinforcement learning scheme with
the LLM outputting probability of the target answer as the reward. We verify
the effectiveness of our method on various red-teaming benchmarks, such as
AdvBench and HH-Harmless. The empirical results demonstrate that Atoxia can
successfully detect safety risks in not only open-source models but also
state-of-the-art black-box models such as GPT-4o.
