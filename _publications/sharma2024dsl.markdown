---
layout: publication
title: 'SPML: A DSL For Defending Language Models Against Prompt Attacks'
authors: Reshabh K Sharma, Vinayak Gupta, Dan Grossman
conference: "Arxiv"
year: 2024
bibkey: sharma2024dsl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11755"}
  - {name: "Code", url: "https://prompt-compiler.github.io/SPML/"}
tags: ['Security', 'Model Architecture', 'GPT', 'Has Code', 'Prompting', 'Applications']
---
Large language models (LLMs) have profoundly transformed natural language
applications, with a growing reliance on instruction-based definitions for
designing chatbots. However, post-deployment the chatbot definitions are fixed
and are vulnerable to attacks by malicious users, emphasizing the need to
prevent unethical applications and financial losses. Existing studies explore
user prompts' impact on LLM-based chatbots, yet practical methods to contain
attacks on application-specific chatbots remain unexplored. This paper presents
System Prompt Meta Language (SPML), a domain-specific language for refining
prompts and monitoring the inputs to the LLM-based chatbots. SPML actively
checks attack prompts, ensuring user inputs align with chatbot definitions to
prevent malicious execution on the LLM backbone, optimizing costs. It also
streamlines chatbot definition crafting with programming language capabilities,
overcoming natural language design challenges. Additionally, we introduce a
groundbreaking benchmark with 1.8k system prompts and 20k user inputs, offering
the inaugural language and benchmark for chatbot definition evaluation.
Experiments across datasets demonstrate SPML's proficiency in understanding
attacker prompts, surpassing models like GPT-4, GPT-3.5, and LLAMA. Our data
and codes are publicly available at: https://prompt-compiler.github.io/SPML/.
