---
layout: publication
title: Llmseceval A Dataset Of Natural Language Prompts For Security Evaluations
authors: Tony Catherine, Mutas Markus, Ferreyra Nicolás E. Díaz, Scandariato Riccardo
conference: "Arxiv"
year: 2023
bibkey: tony2023dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.09384"}
tags: ['Applications', 'Prompting', 'RAG', 'Security', 'Tools']
---
Large Language Models (LLMs) like Codex are powerful tools for performing code completion and code generation tasks as they are trained on billions of lines of code from publicly available sources. Moreover these models are capable of generating code snippets from Natural Language (NL) descriptions by learning languages and programming practices from public GitHub repositories. Although LLMs promise an effortless NL-driven deployment of software applications the security of the code they generate has not been extensively investigated nor documented. In this work we present LLMSecEval a dataset containing 150 NL prompts that can be leveraged for assessing the security performance of such models. Such prompts are NL descriptions of code snippets prone to various security vulnerabilities listed in MITREs Top 25 Common Weakness Enumeration (CWE) ranking. Each prompt in our dataset comes with a secure implementation example to facilitate comparative evaluations against code produced by LLMs. As a practical application we show how LLMSecEval can be used for evaluating the security of snippets automatically generated from NL descriptions.
