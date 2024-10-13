---
layout: publication
title: 'Reliable Reasoning Beyond Natural Language'
authors: Borazjanizadeh Nasim, Piantadosi Steven T.
conference: "Arxiv"
year: 2024
bibkey: borazjanizadeh2024reliable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11373"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Uncategorized']
---
Despite their linguistic competence, Large Language models (LLMs) often
exhibit limitations in their ability to reason reliably and flexibly. To
address this, we propose a neurosymbolic approach that prompts LLMs to extract
and encode all relevant information from a problem statement as logical code
statements, and then use a logic programming language (Prolog) to conduct the
iterative computations of explicit deductive reasoning. Our approach
significantly enhances the performance of LLMs on the standard mathematical
reasoning benchmark, GSM8k, and the Navigate dataset from the BIG-bench
dataset. Additionally, we introduce a novel dataset, the Non-Linear Reasoning
(NLR) dataset, consisting of 55 unique word problems that target the
shortcomings of the next token prediction paradigm of LLMs and require complex
non-linear reasoning but only basic arithmetic skills to solve. Our findings
demonstrate that the integration of Prolog enables LLMs to achieve high
performance on the NLR dataset, which even the most advanced language models
(including GPT4) fail to solve using text only.
