---
layout: publication
title: 'Amulet: Putting Complex Multi-turn Conversations On The Stand With LLM Juries'
authors: Sahana Ramnath, Anurag Mudgil, Brihi Joshi, Skyler Hallinan, Xiang Ren
conference: "Arxiv"
year: 2025
bibkey: ramnath2025putting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20451"}
tags: ['RAG', 'Tools', 'Reinforcement Learning']
---
Today, large language models are widely used as judges to evaluate responses from other language models. Hence, it is imperative to benchmark and improve these LLM-judges on real-world language model usage: a typical human-assistant conversation is lengthy, and shows significant diversity in topics, intents, and requirements across turns, e.g. social interactions, task requests, feedback. We present Amulet, a framework that leverages pertinent linguistic concepts of dialog-acts and maxims to improve the accuracy of LLM-judges on preference data with complex, multi-turn conversational context. Amulet presents valuable insights about (a) the communicative structures and intents present in the conversation (dialog acts), and (b) the satisfaction of conversational principles (maxims) by the preference responses, and uses them to make judgments. On four challenging datasets, Amulet shows that (a) humans frequently (60 to 70 percent of the time) change their intents from one turn of the conversation to the next, and (b) in 75 percent of instances, the preference responses can be differentiated via dialog acts and/or maxims, reiterating the latter's significance in judging such data. Amulet can be used either as a judge by applying the framework to a single LLM, or integrated into a jury with different LLM judges; our judges and juries show strong improvements on relevant baselines for all four datasets.
