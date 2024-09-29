---
layout: publication
title: Copilot Evaluation Harness Evaluating Llm-guided Software Programming
authors: Agarwal Anisha, Chan Aaron, Chandel Shubham, Jang Jinu, Miller Shaun, Moghaddam Roshanak Zilouchian, Mohylevskyy Yevhen, Sundaresan Neel, Tufano Michele
conference: "Arxiv"
year: 2024
bibkey: agarwal2024copilot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14261"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Tools']
---
The integration of Large Language Models (LLMs) into Development Environments (IDEs) has become a focal point in modern software development. LLMs such as OpenAI GPT-3.5/4 and Code Llama offer the potential to significantly augment developer productivity by serving as intelligent chat-driven programming assistants. However utilizing LLMs out of the box is unlikely to be optimal for any given scenario. Rather each system requires the LLM to be honed to its set of heuristics to ensure the best performance. In this paper we introduce the Copilot evaluation harness a set of data and tools for evaluating LLM-guided IDE interactions covering various programming scenarios and languages. We propose our metrics as a more robust and information-dense evaluation than previous state of the art evaluation systems. We design and compute both static and execution based success metrics for scenarios encompassing a wide range of developer tasks including code generation from natural language (generate) documentation generation from code (doc) test case generation (test) bug-fixing (fix) and workspace understanding and query resolution (workspace). These success metrics are designed to evaluate the performance of LLMs within a given IDE and its respective parameter space. Our learnings from evaluating three common LLMs using these metrics can inform the development and validation of future scenarios in LLM guided IDEs.
