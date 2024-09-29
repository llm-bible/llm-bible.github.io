---
layout: publication
title: Tooltalk Evaluating Tool45;usage In A Conversational Setting
authors: Farn Nicholas, Shin Richard
conference: "Arxiv"
year: 2023
bibkey: farn2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10775"}
  - {name: "Code", url: "https://github.com/microsoft/ToolTalk"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have displayed massive improvements in reasoning and decision45;making skills and can hold natural conversations with users. Many recent works seek to augment LLM45;based assistants with external tools so they can access private or up45;to45;date information and carry out actions on behalf of users. To better measure the performance of these assistants this paper introduces ToolTalk a benchmark consisting of complex user intents requiring multi45;step tool usage specified through dialogue. ToolTalk contains 28 tools grouped into 7 plugins and includes a complete simulated implementation of each tool allowing for fully automated evaluation of assistants that rely on execution feedback. ToolTalk also emphasizes tools that externally affect the world rather than only tools for referencing or searching information. We evaluate GPT45;3.5 and GPT45;4 on ToolTalk resulting in success rates of 2637; and 5037; respectively. Our analysis of the errors reveals three major categories and suggests some future directions for improvement. We release ToolTalk at https://github.com/microsoft/ToolTalk.
