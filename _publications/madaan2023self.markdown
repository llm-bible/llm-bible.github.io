---
layout: publication
title: Self45;refine Iterative Refinement With Self45;feedback
authors: Madaan Aman, Tandon Niket, Gupta Prakhar, Hallinan Skyler, Gao Luyu, Wiegreffe Sarah, Alon Uri, Dziri Nouha, Prabhumoye Shrimai, Yang Yiming, Gupta Shashank, Majumder Bodhisattwa Prasad, Hermann Katherine, Welleck Sean, Yazdanbakhsh Amir, Clark Peter
conference: "Arxiv"
year: 2023
bibkey: madaan2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.17651"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Like humans large language models (LLMs) do not always generate the best output on their first try. Motivated by how humans refine their written text we introduce Self45;Refine an approach for improving initial outputs from LLMs through iterative feedback and refinement. The main idea is to generate an initial output using an LLMs; then the same LLMs provides feedback for its output and uses it to refine itself iteratively. Self45;Refine does not require any supervised training data additional training or reinforcement learning and instead uses a single LLM as the generator refiner and feedback provider. We evaluate Self45;Refine across 7 diverse tasks ranging from dialog response generation to mathematical reasoning using state45;of45;the45;art (GPT45;3.5 ChatGPT and GPT45;4) LLMs. Across all evaluated tasks outputs generated with Self45;Refine are preferred by humans and automatic metrics over those generated with the same LLM using conventional one45;step generation improving by ~2037; absolute on average in task performance. Our work demonstrates that even state45;of45;the45;art LLMs like GPT45;4 can be further improved at test time using our simple standalone approach.
