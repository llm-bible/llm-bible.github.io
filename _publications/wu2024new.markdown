---
layout: publication
title: 'WIPI: A New Web Threat For Llm-driven Web Agents'
authors: Fangzhou Wu, Shutong Wu, Yulong Cao, Chaowei Xiao
conference: "Arxiv"
year: 2024
bibkey: wu2024new
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16965"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Efficiency and Optimization', 'Tools', 'RAG', 'GPT', 'Attention Mechanism']
---
With the fast development of large language models (LLMs), LLM-driven Web
Agents (Web Agents for short) have obtained tons of attention due to their
superior capability where LLMs serve as the core part of making decisions like
the human brain equipped with multiple web tools to actively interact with
external deployed websites. As uncountable Web Agents have been released and
such LLM systems are experiencing rapid development and drawing closer to
widespread deployment in our daily lives, an essential and pressing question
arises: "Are these Web Agents secure?". In this paper, we introduce a novel
threat, WIPI, that indirectly controls Web Agent to execute malicious
instructions embedded in publicly accessible webpages. To launch a successful
WIPI works in a black-box environment. This methodology focuses on the form and
content of indirect instructions within external webpages, enhancing the
efficiency and stealthiness of the attack. To evaluate the effectiveness of the
proposed methodology, we conducted extensive experiments using 7 plugin-based
ChatGPT Web Agents, 8 Web GPTs, and 3 different open-source Web Agents. The
results reveal that our methodology achieves an average attack success rate
(ASR) exceeding 90% even in pure black-box scenarios. Moreover, through an
ablation study examining various user prefix instructions, we demonstrated that
the WIPI exhibits strong robustness, maintaining high performance across
diverse prefix instructions.
