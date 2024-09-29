---
layout: publication
title: On the Brittle Foundations of ReAct Prompting for Agentic Large Language Models
authors: Verma Mudit, Bhambri Siddhant, Kambhampati Subbarao
conference: "Arxiv"
year: 2024
bibkey: verma2024brittle
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13966"}
tags: ['Agentic', 'Prompting', 'Reinforcement Learning']
---
The reasoning abilities of Large Language Models (LLMs) remain a topic of debate. Some methods such as ReAct-based prompting have gained popularity for claiming to enhance sequential decision-making abilities of agentic LLMs. However it is unclear what is the source of improvement in LLM reasoning with ReAct based prompting. In this paper we examine these claims of ReAct based prompting in improving agentic LLMs for sequential decision-making. By introducing systematic variations to the input prompt we perform a sensitivity analysis along the claims of ReAct and find that the performance is minimally influenced by the interleaving reasoning trace with action execution or the content of the generated reasoning traces in ReAct contrary to original claims and common usage. Instead the performance of LLMs is driven by the similarity between input example tasks and queries implicitly forcing the prompt designer to provide instance-specific examples which significantly increases the cognitive burden on the human. Our investigation shows that the perceived reasoning abilities of LLMs stem from the exemplar-query similarity and approximate retrieval rather than any inherent reasoning abilities.
