---
layout: publication
title: Promptbreeder Self45;referential Self45;improvement Via Prompt Evolution
authors: Fernando Chrisantha, Banarse Dylan, Michalewski Henryk, Osindero Simon, Rocktäschel Tim
conference: "Arxiv"
year: 2023
bibkey: fernando2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16797"}
tags: ['Pretraining Methods', 'Prompting', 'Training Techniques']
---
Popular prompt strategies like Chain45;of45;Thought Prompting can dramatically improve the reasoning abilities of Large Language Models (LLMs) in various domains. However such hand45;crafted prompt45;strategies are often sub45;optimal. In this paper we present Promptbreeder a general45;purpose self45;referential self45;improvement mechanism that evolves and adapts prompts for a given domain. Driven by an LLM Promptbreeder mutates a population of task45;prompts and subsequently evaluates them for fitness on a training set. Crucially the mutation of these task45;prompts is governed by mutation45;prompts that the LLM generates and improves throughout evolution in a self45;referential way. That is Promptbreeder is not just improving task45;prompts but it is also improving the mutationprompts that improve these task45;prompts. Promptbreeder outperforms state45;of45;the45;art prompt strategies such as Chain45;of45;Thought and Plan45;and45;Solve Prompting on commonly used arithmetic and commonsense reasoning benchmarks. Furthermore Promptbreeder is able to evolve intricate task45;prompts for the challenging problem of hate speech classification.
