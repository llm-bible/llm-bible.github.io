---
layout: publication
title: Remember what you did so you know what to do next
authors: Ciosici Manuel R., Hedges Alex, Kankanampati Yash, Martin Justin, Freedman Marjorie, Weischedel Ralph
conference: "Arxiv"
year: 2023
bibkey: ciosici2023remember
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01468"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We explore using a moderately sized large language model (GPT-J 6B parameters) to create a plan for a simulated robot to achieve 30 classes of goals in ScienceWorld a text game simulator for elementary science experiments. Previously published empirical work claimed that large language models (LLMs) are a poor fit (Wang et al. 2022) compared to reinforcement learning. Using the Markov assumption (a single previous step) the LLM outperforms the reinforcement learning-based approach by a factor of 1.4. When we fill the LLMs input buffer with as many prior steps as possible improvement rises to 3.5x. Even when training on only 6.5 of the training data we observe a 2.2x improvement over the reinforcement-learning-based approach. Our experiments show that performance varies widely across the 30 classes of actions indicating that averaging over tasks can hide significant performance issues. In work contemporaneous with ours Lin et al. (2023) demonstrated a two-part approach (SwiftSage) that uses a small LLM (T5-large) complemented by OpenAIs massive LLMs to achieve outstanding results in ScienceWorld. Our 6-B parameter single-stage GPT-J matches the performance of SwiftSages two-stage architecture when it incorporates GPT-3.5 turbo which has 29-times more parameters than GPT-J.
