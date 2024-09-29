---
layout: publication
title: Askit: Unified Programming Interface For Programming With Large Language Models
authors: Okuda Katsumi, Amarasinghe Saman
conference: "Arxiv"
year: 2023
bibkey: okuda2023unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15645"}
  - {name: "Code", url: "https://github.com/katsumiok/ts-askit"}
  - {name: "Code", url: "https://github.com/katsumiok/pyaskit,"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) exhibit a unique phenomenon known as emergent abilities demonstrating adeptness across numerous tasks from text summarization to code generation. While these abilities open up novel avenues in software design and crafting their incorporation presents substantial challenges. Developers face decisions regarding the use of LLMs for directly performing tasks within applications as well as for generating and executing code to accomplish these tasks. Moreover effective prompt design becomes a critical concern given the necessity of extracting data from natural language outputs. To address these complexities this paper introduces AskIt a domain-specific language (DSL) specifically designed for LLMs. AskIt simplifies LLM integration by providing a unified interface that not only allows for direct task execution using LLMs but also supports the entire cycle of code generation and execution. This dual capability is achieved through (1) type-guided output control (2) template-based function definitions and (3) prompt generation for both usage modes. Our evaluations underscore AskIts effectiveness. Across 50 tasks AskIt generated concise prompts achieving a 16.14 37; reduction in prompt length compared to benchmarks. Additionally by enabling a seamless transition between using LLMs directly in applications and for generating code AskIt achieved significant efficiency improvements as observed in our GSM8K benchmark experiments. The implementations of AskIt in TypeScript and Python are available at https://github.com/katsumiok/ts-askit and https://github.com/katsumiok/pyaskit, respectively.
