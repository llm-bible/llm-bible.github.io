---
layout: publication
title: Adaptable Logical Control For Large Language Models
authors: Zhang Honghua, Kung Po-nien, Yoshida Masahiro, Broeck Guy Van Den, Peng Nanyun
conference: "Arxiv"
year: 2024
bibkey: zhang2024adaptable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13892"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Despite the success of Large Language Models (LLMs) on various tasks following human instructions controlling model generation at inference time poses a persistent challenge. In this paper we introduce Ctrl45;G an adaptable framework that facilitates tractable and flexible control of LLM generation to reliably follow logical constraints. Ctrl45;G combines any production45;ready LLM with a Hidden Markov Model enabling LLM outputs to adhere to logical constraints represented as deterministic finite automata. We show that Ctrl45;G when applied to a TULU245;7B model outperforms GPT3.5 and GPT4 on the task of interactive text editing specifically for the task of generating text insertions/continuations following logical constraints Ctrl45;G achieves over 3037; higher satisfaction rate in human evaluation compared to GPT4. When applied to medium45;size language models (e.g. GPT245;large) Ctrl45;G also beats its counterparts for constrained generation by large margins on standard benchmarks. Additionally as a proof45;of45;concept study we experiment Ctrl45;G on the Grade School Math benchmark to assist LLM reasoning foreshadowing the application of Ctrl45;G as well as other constrained generation approaches beyond traditional language generation tasks.
