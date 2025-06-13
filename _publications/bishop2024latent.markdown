---
layout: publication
title: 'Latent State Estimation Helps UI Agents To Reason'
authors: William E Bishop, Alice Li, Christopher Rawles, Oriana Riva
conference: "Arxiv"
year: 2024
bibkey: bishop2024latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11120"}
tags: ['Agentic', 'RAG', 'Prompting', 'Reinforcement Learning']
---
A common problem for agents operating in real-world environments is that the
response of an environment to their actions may be non-deterministic and
observed through noise. This renders environmental state and progress towards
completing a task latent. Despite recent impressive demonstrations of LLM's
reasoning abilities on various benchmarks, whether LLMs can build estimates of
latent state and leverage them for reasoning has not been explicitly studied.
We investigate this problem in the real-world domain of autonomous UI agents.
We establish that appropriately prompting LLMs in a zero-shot manner can be
formally understood as forming point estimates of latent state in a textual
space. In the context of autonomous UI agents we then show that LLMs used in
this manner are more than \\(76%\\) accurate at inferring various aspects of
latent state, such as performed (vs. commanded) actions and task progression.
Using both public and internal benchmarks and three reasoning methods
(zero-shot, CoT-SC & ReAct), we show that LLM-powered agents that explicitly
estimate and reason about latent state are able to successfully complete up to
1.6x more tasks than those that do not.
