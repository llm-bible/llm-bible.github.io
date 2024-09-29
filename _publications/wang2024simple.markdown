---
layout: publication
title: Sibyl\: Simple Yet Effective Agent Framework For Complex Real-world Reasoning
authors: Wang Yulong, Shen Tianhao, Liu Lifeng, Xie Jian
conference: "Arxiv"
year: 2024
bibkey: wang2024simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10718"}
tags: ['Agentic', 'Applications', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Existing agents based on large language models (LLMs) demonstrate robust problem-solving capabilities by integrating LLMs inherent knowledge strong in-context learning and zero-shot capabilities and the use of tools combined with intricately designed LLM invocation workflows by humans. However these agents still exhibit shortcomings in long-term reasoning and under-use the potential of existing tools leading to noticeable deficiencies in complex real-world reasoning scenarios. To address these limitations we introduce Sibyl a simple yet powerful LLM-based agent framework designed to tackle complex reasoning tasks by efficiently leveraging a minimal set of tools. Drawing inspiration from Global Workspace Theory Sibyl incorporates a global workspace to enhance the management and sharing of knowledge and conversation history throughout the system. Furthermore guided by Society of Mind Theory Sibyl implements a multi-agent debate-based jury to self-refine the final answers ensuring a comprehensive and balanced approach. This approach aims to reduce system complexity while expanding the scope of problems solvable-from matters typically resolved by humans in minutes to those requiring hours or even days thus facilitating a shift from System-1 to System-2 thinking. Sibyl has been designed with a focus on scalability and ease of debugging by incorporating the concept of reentrancy from functional programming from its inception with the aim of seamless and low effort integration in other LLM applications to improve capabilities. Our experimental results on the GAIA benchmark test set reveal that the Sibyl agent instantiated with GPT-4 achieves state-of-the-art performance with an average score of 34.5537; compared to other agents based on GPT-4. We hope that Sibyl can inspire more reliable and reusable LLM-based agent solutions to address complex real-world reasoning tasks.
