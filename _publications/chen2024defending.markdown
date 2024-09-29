---
layout: publication
title: 'Struq: Defending Against Prompt Injection With Structured Queries'
authors: Chen Sizhe, Piet Julien, Sitawarin Chawin, Wagner David
conference: "Arxiv"
year: 2024
bibkey: chen2024defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06363"}
  - {name: "Code", url: "https://github.com/Sizhe-Chen/PromptInjectionDefense"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Recent advances in Large Language Models (LLMs) enable exciting LLM-integrated applications which perform text-based tasks by utilizing their advanced language understanding capabilities. However as LLMs have improved so have the attacks against them. Prompt injection attacks are an important threat they trick the model to deviate from the original applications instructions and instead follow user directives. These attacks rely on the LLMs ability to follow instructions and inability to separate the prompts and user data. We introduce structured queries a general approach to tackle this problem. Structured queries separate prompts and data into two channels. We implement a system that supports structured queries. This system is made of (1) a secure front-end that formats a prompt and user data into a special format and (2) a specially trained LLM that can produce high-quality outputs from these inputs. The LLM is trained using a novel fine-tuning strategy we convert a base (non-instruction-tuned) LLM to a structured instruction-tuned model that will only follow instructions in the prompt portion of a query. To do so we augment standard instruction tuning datasets with examples that also include instructions in the data portion of the query and fine-tune the model to ignore these. Our system significantly improves resistance to prompt injection attacks with little or no impact on utility. Our code is released at https://github.com/Sizhe-Chen/PromptInjectionDefense."
