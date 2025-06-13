---
layout: publication
title: 'Mutagrep: Execution-free Repository-grounded Plan Search For Code-use'
authors: Zaid Khan, Ali Farhadi, Ranjay Krishna, Luca Weihs, Mohit Bansal, Tanmay Gupta
conference: "Arxiv"
year: 2025
bibkey: khan2025execution
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15872"}
tags: ['Model Architecture', 'GPT', 'Tools']
---
When a human requests an LLM to complete a coding task using functionality
from a large code repository, how do we provide context from the repo to the
LLM? One approach is to add the entire repo to the LLM's context window.
However, most tasks involve only fraction of symbols from a repo, longer
contexts are detrimental to the LLM's reasoning abilities, and context windows
are not unlimited. Alternatively, we could emulate the human ability to
navigate a large repo, pick out the right functionality, and form a plan to
solve the task. We propose MutaGReP (Mutation-guided Grounded Repository Plan
Search), an approach to search for plans that decompose a user request into
natural language steps grounded in the codebase. MutaGReP performs neural tree
search in plan space, exploring by mutating plans and using a symbol retriever
for grounding. On the challenging LongCodeArena benchmark, our plans use less
than 5% of the 128K context window for GPT-4o but rival the coding performance
of GPT-4o with a context window filled with the repo. Plans produced by
MutaGReP allow Qwen 2.5 Coder 32B and 72B to match the performance of GPT-4o
with full repo context and enable progress on the hardest LongCodeArena tasks.
Project page: zaidkhan.me/MutaGReP
