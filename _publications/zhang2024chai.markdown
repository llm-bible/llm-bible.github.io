---
layout: publication
title: 'CHAI For Llms: Improving Code-mixed Translation In Large Language Models Through Reinforcement Learning With AI Feedback'
authors: Wenbo Zhang, Aditya Majumdar, Amulya Yadav
conference: "Arxiv"
year: 2024
bibkey: zhang2024chai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.09073"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Attention Mechanism']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities across
various NLP tasks but struggle with code-mixed (or code-switched) language
understanding. For example, prior work benchmarking the performance of
multilingual LLMs on code-mixed translation tasks has demonstrated that current
state-of-the-art multilingual LLMs are ineffective in dealing with code-mixed
languages. However, the question of how to improve the capability of
multilingual LLMs to handle code-mixed language has not received any attention
to date. In this paper, we tackle this research gap by proposing CHAI, a novel
general-purpose framework for improving the ability of multilingual LLMs to
handle code-mixed languages. CHAI relies on three novel contributions made in
this paper. First, we explore the ability of LLMs to provide accurate
annotations for code-mixed translation tasks. Second, we leverage this ability
of LLMs as annotators to generate preference data for code-mixed translation
tasks at scale, which are then used within a reinforcement learning from AI
feedback (RLAIF) procedure to improve LLMs' capability on code-mixed tasks.
Third, we conduct a rigorous experimental evaluation across various real-world
datasets and settings. Our analysis shows that CHAI-powered LLMs outperform
state-of-the-art open-source LLMs by 25.66% (in terms of win rate adjudicated
by human annotators) in code-mixed translation tasks. This work represents a
first step towards developing more inclusive code-mixed LLMs.
