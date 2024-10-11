---
layout: publication
title: 'AIOS Compiler: LLM As Interpreter For Natural Language Programming And Flow Programming Of AI Agents'
authors: Xu Shuyuan, Li Zelong, Mei Kai, Zhang Yongfeng
conference: "Arxiv"
year: 2024
bibkey: xu2024aios
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06907"}
  - {name: "Code", url: "https://github.com/agiresearch/CoRE,"}
  - {name: "Code", url: "https://github.com/agiresearch/OpenAGI,"}
  - {name: "Code", url: "https://github.com/agiresearch/AIOS"}
tags: ['Agentic', 'Has Code', 'Tools', 'Uncategorized']
---
Since their inception, programming languages have trended towards greater readability and lower barriers for programmers. Following this trend, natural language can be a promising type of programming language that provides great flexibility and usability and helps towards the democracy of programming. However, the inherent vagueness, ambiguity, and verbosity of natural language pose significant challenges in developing an interpreter that can accurately understand the programming logic and execute instructions written in natural language. Fortunately, recent advancements in Large Language Models (LLMs) have demonstrated remarkable proficiency in interpreting complex natural language. Inspired by this, we develop a novel system for Code Representation and Execution (CoRE), which employs LLM as interpreter to interpret and execute natural language instructions. The proposed system unifies natural language programming, pseudo-code programming, and flow programming under the same representation for constructing language agents, while LLM serves as the interpreter to interpret and execute the agent programs. In this paper, we begin with defining the programming syntax that structures natural language instructions logically. During the execution, we incorporate external memory to minimize redundancy. Furthermore, we equip the designed interpreter with the capability to invoke external tools, compensating for the limitations of LLM in specialized domains or when accessing real-time information. This work is open-source at https://github.com/agiresearch/CoRE, https://github.com/agiresearch/OpenAGI, and https://github.com/agiresearch/AIOS.
