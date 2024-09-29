---
layout: publication
title: Zero45;shot Goal45;directed Dialogue Via RL On Imagined Conversations
authors: Hong Joey, Levine Sergey, Dragan Anca
conference: "Arxiv"
year: 2023
bibkey: hong2023zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05584"}
tags: ['Agentic', 'Applications', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have emerged as powerful and general solutions to many natural language tasks. However many of the most important applications of language generation are interactive where an agent has to talk to a person to reach a desired outcome. For example a teacher might try to understand their students current comprehension level to tailor their instruction accordingly and a travel agent might ask questions of their customer to understand their preferences in order to recommend activities they might enjoy. LLMs trained with supervised fine45;tuning or single45;step RL as with standard RLHF might struggle which tasks that require such goal45;directed behavior since they are not trained to optimize for overall conversational outcomes after multiple turns of interaction. In this work we explore a new method for adapting LLMs with RL for such goal45;directed dialogue. Our key insight is that though LLMs might not effectively solve goal45;directed dialogue tasks out of the box they can provide useful data for solving such tasks by simulating suboptimal but human45;like behaviors. Given a textual description of a goal45;directed dialogue task we leverage LLMs to sample diverse synthetic rollouts of hypothetical in45;domain human45;human interactions. Our algorithm then utilizes this dataset with offline reinforcement learning to train an interactive conversational agent that can optimize goal45;directed objectives over multiple turns. In effect the LLM produces examples of possible interactions and RL then processes these examples to learn to perform more optimal interactions. Empirically we show that our proposed approach achieves state45;of45;the45;art performance in various goal45;directed dialogue tasks that include teaching and preference elicitation.
