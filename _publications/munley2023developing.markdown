---
layout: publication
title: LLM4VV Developing Llm45;driven Testsuite For Compiler Validation
authors: Munley Christian, Jarmusch Aaron, Chandrasekaran Sunita
conference: "Arxiv"
year: 2023
bibkey: munley2023developing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04963"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
Large language models (LLMs) are a new and powerful tool for a wide span of applications involving natural language and demonstrate impressive code generation abilities. The goal of this work is to automatically generate tests and use these tests to validate and verify compiler implementations of a directive45;based parallel programming paradigm OpenACC. To do so in this paper we explore the capabilities of state45;of45;the45;art LLMs including open45;source LLMs 45;45; Meta Codellama Phind fine45;tuned version of Codellama Deepseek Deepseek Coder and closed45;source LLMs 45;45; OpenAI GPT45;3.545;Turbo and GPT45;445;Turbo. We further fine45;tuned the open45;source LLMs and GPT45;3.545;Turbo using our own testsuite dataset along with using the OpenACC specification. We also explored these LLMs using various prompt engineering techniques that include code template template with retrieval45;augmented generation (RAG) one45;shot example one45;shot with RAG expressive prompt with code template and RAG. This paper highlights our findings from over 5000 tests generated via all the above mentioned methods. Our contributions include (a) exploring the capabilities of the latest and relevant LLMs for code generation (b) investigating fine45;tuning and prompt methods and (c) analyzing the outcome of LLMs generated tests including manually analysis of representative set of tests. We found the LLM Deepseek45;Coder45;33b45;Instruct produced the most passing tests followed by GPT45;445;Turbo.
