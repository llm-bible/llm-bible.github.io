---
layout: publication
title: 'Steward: Natural Language Web Automation'
authors: Brian Tang, Kang G. Shin
conference: "Arxiv"
year: 2024
bibkey: tang2024natural
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15441'}
tags: ['RAG', 'Efficiency and Optimization', 'Tools', 'Merging', 'RecSys']
---
Recently, large language models (LLMs) have demonstrated exceptional
capabilities in serving as the foundation for AI assistants. One emerging
application of LLMs, navigating through websites and interacting with UI
elements across various web pages, remains somewhat underexplored. We introduce
Steward, a novel LLM-powered web automation tool designed to serve as a
cost-effective, scalable, end-to-end solution for automating web interactions.
Traditional browser automation frameworks like Selenium, Puppeteer, and
Playwright are not scalable for extensive web interaction tasks, such as
studying recommendation algorithms on platforms like YouTube and Twitter. These
frameworks require manual coding of interactions, limiting their utility in
large-scale or dynamic contexts. Steward addresses these limitations by
integrating LLM capabilities with browser automation, allowing for natural
language-driven interaction with websites. Steward operates by receiving
natural language instructions and reactively planning and executing a sequence
of actions on websites, looping until completion, making it a practical tool
for developers and researchers to use. It achieves high efficiency, completing
actions in 8.52 to 10.14 seconds at a cost of \\(0.028 per action or an average
of \\)0.18 per task, which is further reduced to 4.8 seconds and $0.022 through a
caching mechanism. It runs tasks on real websites with a 40% completion success
rate. We discuss various design and implementation challenges, including state
representation, action sequence selection, system responsiveness, detecting
task completion, and caching implementation.
