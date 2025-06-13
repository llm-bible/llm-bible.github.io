---
layout: publication
title: 'Sosecure: Safer Code Generation With RAG And Stackoverflow Discussions'
authors: Manisha Mukherjee, Vincent J. Hellendoorn
conference: "Arxiv"
year: 2025
bibkey: mukherjee2025safer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13654'}
tags: ['RAG', 'Security', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Applications', 'Pretraining Methods']
---
Large Language Models (LLMs) are widely used for automated code generation.
Their reliance on infrequently updated pretraining data leaves them unaware of
newly discovered vulnerabilities and evolving security standards, making them
prone to producing insecure code. In contrast, developer communities on Stack
Overflow (SO) provide an ever-evolving repository of knowledge, where security
vulnerabilities are actively discussed and addressed through collective
expertise. These community-driven insights remain largely untapped by LLMs.
This paper introduces SOSecure, a Retrieval-Augmented Generation (RAG) system
that leverages the collective security expertise found in SO discussions to
improve the security of LLM-generated code. We build a security-focused
knowledge base by extracting SO answers and comments that explicitly identify
vulnerabilities. Unlike common uses of RAG, SOSecure triggers after code has
been generated to find discussions that identify flaws in similar code. These
are used in a prompt to an LLM to consider revising the code. Evaluation across
three datasets (SALLM, LLMSecEval, and LMSys) show that SOSecure achieves
strong fix rates of 71.7%, 91.3%, and 96.7% respectively, compared to prompting
GPT-4 without relevant discussions (49.1%, 56.5%, and 37.5%), and outperforms
multiple other baselines. SOSecure operates as a language-agnostic complement
to existing LLMs, without requiring retraining or fine-tuning, making it easy
to deploy. Our results underscore the importance of maintaining active
developer forums, which have dropped substantially in usage with LLM adoptions.
