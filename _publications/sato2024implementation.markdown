---
layout: publication
title: 'An Implementation Of Werewolf Agent That Does Not Truly Trust Llms'
authors: Sato Takehiro, Ozaki Shintaro, Yokoyama Daisaku
conference: "Arxiv"
year: 2024
bibkey: sato2024implementation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01575"}
tags: ['Agentic', 'Uncategorized']
---
Werewolf is an incomplete information game, which has several challenges when creating a computer agent as a player given the lack of understanding of the situation and individuality of utterance (e.g., computer agents are not capable of characterful utterance or situational lying). We propose a werewolf agent that solves some of those difficulties by combining a Large Language Model (LLM) and a rule-based algorithm. In particular, our agent uses a rule-based algorithm to select an output either from an LLM or a template prepared beforehand based on the results of analyzing conversation history using an LLM. It allows the agent to refute in specific situations, identify when to end the conversation, and behave with persona. This approach mitigated conversational inconsistencies and facilitated logical utterance as a result. We also conducted a qualitative evaluation, which resulted in our agent being perceived as more human-like compared to an unmodified LLM. The agent is freely available for contributing to advance the research in the field of Werewolf game.
