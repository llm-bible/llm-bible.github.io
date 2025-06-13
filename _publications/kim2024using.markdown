---
layout: publication
title: 'Using Llms To Investigate Correlations Of Conversational Follow-up Queries With User Satisfaction'
authors: Hyunwoo Kim, Yoonseo Choi, Taehyun Yang, Honggu Lee, Chaneon Park, Yongju Lee, Jin Young Kim, Juho Kim
conference: "Arxiv"
year: 2024
bibkey: kim2024using
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.13166'}
tags: ['Reinforcement Learning']
---
With large language models (LLMs), conversational search engines shift how
users retrieve information from the web by enabling natural conversations to
express their search intents over multiple turns. Users' natural conversation
embodies rich but implicit signals of users' search intents and evaluation of
search results to understand user experience with the system. However, it is
underexplored how and why users ask follow-up queries to continue conversations
with conversational search engines and how the follow-up queries signal users'
satisfaction. From qualitative analysis of 250 conversational turns from an
in-lab user evaluation of Naver Cue:, a commercial conversational search
engine, we propose a taxonomy of 18 users' follow-up query patterns from
conversational search, comprising two major axes: (1) users' motivations behind
continuing conversations (N = 7) and (2) actions of follow-up queries (N = 11).
Compared to the existing literature on query reformulations, we uncovered a new
set of motivations and actions behind follow-up queries, including asking for
subjective opinions or providing natural language feedback on the engine's
responses. To analyze conversational search logs with our taxonomy in a
scalable and efficient manner, we built an LLM-powered classifier (73%
accuracy). With our classifier, we analyzed 2,061 conversational tuples
collected from real-world usage logs of Cue: and examined how the conversation
patterns from our taxonomy correlates with satisfaction. Our initial findings
suggest some signals of dissatisfactions, such as Clarifying Queries, Excluding
Condition, and Substituting Condition with follow-up queries. We envision our
approach could contribute to automated evaluation of conversation search
experience by providing satisfaction signals and grounds for realistic user
simulations.
