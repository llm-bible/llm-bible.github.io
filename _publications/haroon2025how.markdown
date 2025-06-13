---
layout: publication
title: 'How Accurately Do Large Language Models Understand Code?'
authors: Sabaat Haroon, Ahmad Faraz Khan, Ahmad Humayun, Waris Gill, Abdul Haddi Amjad, Ali R. Butt, Mohammad Taha Khan, Muhammad Ali Gulzar
conference: "Arxiv"
year: 2025
bibkey: haroon2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04372"}
tags: ['Training Techniques', 'Survey Paper', 'Tokenization', 'Reinforcement Learning']
---
Large Language Models (LLMs) are increasingly used in post-development tasks
such as code repair and testing. A key factor in these tasks' success is the
model's deep understanding of code. However, the extent to which LLMs truly
understand code remains largely unevaluated. Quantifying code comprehension is
challenging due to its abstract nature and the lack of a standardized metric.
Previously, this was assessed through developer surveys, which are not feasible
for evaluating LLMs. Existing LLM benchmarks focus primarily on code
generation, fundamentally different from code comprehension. Additionally,
fixed benchmarks quickly become obsolete as they become part of the training
data. This paper presents the first large-scale empirical investigation into
LLMs' ability to understand code. Inspired by mutation testing, we use an LLM's
fault-finding ability as a proxy for its deep code understanding. This approach
is based on the insight that a model capable of identifying subtle functional
discrepancies must understand the code well. We inject faults in real-world
programs and ask the LLM to localize them, ensuring the specifications suffice
for fault localization. Next, we apply semantic-preserving code mutations
(SPMs) to the faulty programs and test whether the LLMs still locate the
faults, verifying their confidence in code understanding. We evaluate nine
popular LLMs on 600,010 debugging tasks from 670 Java and 637 Python programs.
We find that LLMs lose the ability to debug the same bug in 78% of faulty
programs when SPMs are applied, indicating a shallow understanding of code and
reliance on features irrelevant to semantics. We also find that LLMs understand
code earlier in the program better than later. This suggests that LLMs' code
comprehension remains tied to lexical and syntactic features due to
tokenization designed for natural languages, which overlooks code semantics.
