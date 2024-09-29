---
layout: publication
title: UGIF UI Grounded Instruction Following
authors: Venkatesh Sagar Gubbi, Talukdar Partha, Narayanan Srini
conference: "Arxiv"
year: 2022
bibkey: venkatesh2022ui
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.07615"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Smartphone users often find it difficult to navigate myriad menus to perform common tasks such as How to block calls from unknown numbers. Currently help documents with step45;by45;step instructions are manually written to aid the user. The user experience can be further enhanced by grounding the instructions in the help document to the UI and overlaying a tutorial on the phone UI. To build such tutorials several natural language processing components including retrieval parsing and grounding are necessary but there isnt any relevant dataset for such a task. Thus we introduce UGIF45;DataSet a multi45;lingual multi45;modal UI grounded dataset for step45;by45;step task completion on the smartphone containing 4184 tasks across 8 languages. As an initial approach to this problem we propose retrieving the relevant instruction steps based on the users query and parsing the steps using Large Language Models (LLMs) to generate macros that can be executed on45;device. The instruction steps are often available only in English so the challenge includes cross45;modal cross45;lingual retrieval of English how45;to pages from user queries in many languages and mapping English instruction steps to UI in a potentially different language. We compare the performance of different LLMs including PaLM and GPT45;3 and find that the end45;to45;end task completion rate is 4837; for English UI but the performance drops to 3237; for other languages. We analyze the common failure modes of existing models on this task and point out areas for improvement.
