---
layout: publication
title: Repository45;level Prompt Generation For Large Language Models Of Code
authors: Shrivastava Disha, Larochelle Hugo, Tarlow Daniel
conference: "ICML"
year: 2022
bibkey: shrivastava2022repository
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.12839"}
  - {name: "Code", url: "https://github.com/shrivastavadisha/repo&#95;level&#95;prompt&#95;generation&#125;"}
tags: ['Has Code', 'Prompting', 'Reinforcement Learning', 'Tools']
---
With the success of large language models (LLMs) of code and their use as code assistants (e.g. Codex used in GitHub Copilot) techniques for introducing domain45;specific knowledge in the prompt design process become important. In this work we propose a framework called Repo45;Level Prompt Generator that learns to generate example45;specific prompts using prompt proposals. The prompt proposals take context from the entire repository thereby incorporating both the structure of the repository and the context from other relevant files (e.g. imports parent class files). Our technique doesnt require any access to the weights of the LLM making it applicable in cases where we only have black45;box access to the LLM. We conduct experiments on the task of single45;line code45;autocompletion using code repositories taken from Google Code archives. We demonstrate that an oracle constructed from our prompt proposals gives a remarkably high relative improvement of 3637; over Codex showing the quality of these proposals. Further we show that when we train a model to predict a prompt proposal we can achieve significant performance gains over Codex and other baselines. We release our code data and trained checkpoints at url123;https://github.com/shrivastavadisha/repo&#95;level&#95;prompt&#95;generation&#125;.
