---
layout: publication
title: Long45;range Modeling Of Source Code Files With Ewash Extended Window Access By Syntax Hierarchy
authors: Clement Colin B., Lu Shuai, Liu Xiaoyu, Tufano Michele, Drain Dawn, Duan Nan, Sundaresan Neel, Svyatkovskiy Alexey
conference: "Arxiv"
year: 2021
bibkey: clement2021long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.08780"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Statistical language modeling and translation with transformers have found many successful applications in program understanding and generation tasks setting high benchmarks for tools in modern software development environments. The finite context window of these neural models means however that they will be unable to leverage the entire relevant context of large files and packages for any given task. While there are many efforts to extend the context window we introduce an architecture45;independent approach for leveraging the syntactic hierarchies of source code for incorporating entire file45;level context into a fixed45;length window. Using concrete syntax trees of each source file we extract syntactic hierarchies and integrate them into context window by selectively removing from view more specific less relevant scopes for a given task. We evaluate this approach on code generation tasks and joint translation of natural language and source code in Python programming language achieving a new state45;of45;the45;art in code completion and summarization for Python in the CodeXGLUE benchmark. We also introduce new CodeXGLUE benchmarks for user45;experience45;motivated tasks code completion with normalized literals method body completion/code summarization conditioned on file45;level context.
