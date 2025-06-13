---
layout: publication
title: 'A Reliable Common-sense Reasoning Socialbot Built Using Llms And Goal-directed ASP'
authors: Yankai Zeng, Abhiramon Rajashekharan, Kinjal Basu, Huaduo Wang, Joaquín Arias, Gopal Gupta
conference: "Theory and Practice of Logic Programming 24 (2024) 606-627"
year: 2024
bibkey: zeng2024reliable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18498"}
tags: ['Tools', 'GPT', 'Attention Mechanism', 'Model Architecture']
---
The development of large language models (LLMs), such as GPT, has enabled the
construction of several socialbots, like ChatGPT, that are receiving a lot of
attention for their ability to simulate a human conversation. However, the
conversation is not guided by a goal and is hard to control. In addition,
because LLMs rely more on pattern recognition than deductive reasoning, they
can give confusing answers and have difficulty integrating multiple topics into
a cohesive response. These limitations often lead the LLM to deviate from the
main topic to keep the conversation interesting. We propose AutoCompanion, a
socialbot that uses an LLM model to translate natural language into predicates
(and vice versa) and employs commonsense reasoning based on Answer Set
Programming (ASP) to hold a social conversation with a human. In particular, we
rely on s(CASP), a goal-directed implementation of ASP as the backend. This
paper presents the framework design and how an LLM is used to parse user
messages and generate a response from the s(CASP) engine output. To validate
our proposal, we describe (real) conversations in which the chatbot's goal is
to keep the user entertained by talking about movies and books, and s(CASP)
ensures (i) correctness of answers, (ii) coherence (and precision) during the
conversation, which it dynamically regulates to achieve its specific purpose,
and (iii) no deviation from the main topic.
