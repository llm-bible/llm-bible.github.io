---
layout: publication
title: 'Lockpicking Llms: A Logit-based Jailbreak Using Token-level Manipulation'
authors: Yuxi Li, Yi Liu, Yuekang Li, Ling Shi, Gelei Deng, Shengquan Chen, Kailong Wang
conference: "Arxiv"
year: 2024
bibkey: li2024lockpicking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13068"}
tags: ['RAG', 'Efficiency and Optimization', 'Security']
---
Large language models (LLMs) have transformed the field of natural language
processing, but they remain susceptible to jailbreaking attacks that exploit
their capabilities to generate unintended and potentially harmful content.
Existing token-level jailbreaking techniques, while effective, face scalability
and efficiency challenges, especially as models undergo frequent updates and
incorporate advanced defensive measures. In this paper, we introduce JailMine,
an innovative token-level manipulation approach that addresses these
limitations effectively. JailMine employs an automated "mining" process to
elicit malicious responses from LLMs by strategically selecting affirmative
outputs and iteratively reducing the likelihood of rejection. Through rigorous
testing across multiple well-known LLMs and datasets, we demonstrate JailMine's
effectiveness and efficiency, achieving a significant average reduction of 86%
in time consumed while maintaining high success rates averaging 95%, even in
the face of evolving defensive strategies. Our work contributes to the ongoing
effort to assess and mitigate the vulnerability of LLMs to jailbreaking
attacks, underscoring the importance of continued vigilance and proactive
measures to enhance the security and reliability of these powerful language
models.
