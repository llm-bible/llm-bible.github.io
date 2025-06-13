---
layout: publication
title: 'Refusal-trained Llms Are Easily Jailbroken As Browser Agents'
authors: Priyanshu Kumar, Elaine Lau, Saranya Vijayakumar, Tu Trinh, Scale Red Team, Elaine Chang, Vaughn Robinson, Sean Hendryx, Shuyan Zhou, Matt Fredrikson, Summer Yue, Zifan Wang
conference: "Arxiv"
year: 2024
bibkey: kumar2024refusal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13886'}
tags: ['Agentic', 'Security', 'Model Architecture', 'Applications', 'Tools', 'GPT', 'Reinforcement Learning', 'Responsible AI']
---
For safety reasons, large language models (LLMs) are trained to refuse
harmful user instructions, such as assisting dangerous activities. We study an
open question in this work: does the desired safety refusal, typically enforced
in chat contexts, generalize to non-chat and agentic use cases? Unlike
chatbots, LLM agents equipped with general-purpose tools, such as web browsers
and mobile devices, can directly influence the real world, making it even more
crucial to refuse harmful instructions. In this work, we primarily focus on
red-teaming browser agents, LLMs that manipulate information via web browsers.
To this end, we introduce Browser Agent Red teaming Toolkit (BrowserART), a
comprehensive test suite designed specifically for red-teaming browser agents.
BrowserART is consist of 100 diverse browser-related harmful behaviors
(including original behaviors and ones sourced from HarmBench [Mazeika et al.,
2024] and AirBench 2024 [Zeng et al., 2024b]) across both synthetic and real
websites. Our empirical study on state-of-the-art browser agents reveals that,
while the backbone LLM refuses harmful instructions as a chatbot, the
corresponding agent does not. Moreover, attack methods designed to jailbreak
refusal-trained LLMs in the chat settings transfer effectively to browser
agents. With human rewrites, GPT-4o and o1-preview-based browser agents
attempted 98 and 63 harmful behaviors (out of 100), respectively. We publicly
release BrowserART and call on LLM developers, policymakers, and agent
developers to collaborate on improving agent safety
