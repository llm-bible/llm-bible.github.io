---
layout: publication
title: 'Improving LLM Reasoning With Multi-agent Tree-of-thought Validator Agent'
authors: Fatemeh Haji, Mazal Bethany, Maryam Tabar, Jason Chiang, Anthony Rios, Peyman Najafirad
conference: "Arxiv"
year: 2024
bibkey: haji2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11527'}
  - {name: "Code", url: 'https://github.com/SecureAIAutonomyLab/MA-ToT'}
tags: ['Agentic', 'Has Code', 'RAG', 'Security', 'Fine-Tuning']
---
Multi-agent strategies have emerged as a promising approach to enhance the
reasoning abilities of Large Language Models (LLMs) by assigning specialized
roles in the problem-solving process. Concurrently, Tree of Thoughts (ToT)
methods have shown potential in improving reasoning for complex
question-answering tasks by exploring diverse reasoning paths. A critical
limitation in multi-agent reasoning is the 'Reasoner' agent's shallow
exploration of reasoning paths. While ToT strategies could help mitigate this
problem, they may generate flawed reasoning branches, which could harm the
trustworthiness of the final answer. To leverage the strengths of both
multi-agent reasoning and ToT strategies, we introduce a novel approach
combining ToT-based Reasoner agents with a Thought Validator agent. Multiple
Reasoner agents operate in parallel, employing ToT to explore diverse reasoning
paths. The Thought Validator then scrutinizes these paths, considering a
Reasoner's conclusion only if its reasoning is valid. This method enables a
more robust voting strategy by discarding faulty reasoning paths, enhancing the
system's ability to tackle tasks requiring systematic and trustworthy
reasoning. Our method demonstrates superior performance compared to existing
techniques when evaluated on the GSM8K dataset, outperforming the standard ToT
strategy by an average 5.6% across four LLMs. The code and related content can
be found in: https://github.com/SecureAIAutonomyLab/MA-ToT
