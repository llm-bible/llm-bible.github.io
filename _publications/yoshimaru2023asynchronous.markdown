---
layout: publication
title: 'Asyncmld: Asynchronous Multi-llm Framework For Dialogue Recommendation System'
authors: Yoshimaru Naoki, Okuma Motoharu, Iio Takamasa, Hatano Kenji
conference: "Arxiv"
year: 2023
bibkey: yoshimaru2023asynchronous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.13925"}
tags: ['Agentic', 'Efficiency And Optimization', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
We have reached a practical and realistic phase in human-support dialogue
agents by developing a large language model (LLM). However, when requiring
expert knowledge or anticipating the utterance content using the massive size
of the dialogue database, we still need help with the utterance content's
effectiveness and the efficiency of its output speed, even if using LLM.
Therefore, we propose a framework that uses LLM asynchronously in the part of
the system that returns an appropriate response and in the part that
understands the user's intention and searches the database. In particular,
noting that it takes time for the robot to speak, threading related to database
searches is performed while the robot is speaking.
