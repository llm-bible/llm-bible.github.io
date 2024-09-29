---
layout: publication
title: Guiding Enumerative Program Synthesis With Large Language Models
authors: Li Yixuan, Parsert Julian, Polgreen Elizabeth
conference: "Arxiv"
year: 2024
bibkey: li2024guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03997"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Tools']
---
Pre45;trained Large Language Models (LLMs) are beginning to dominate the discourse around automatic code generation with natural language specifications. In contrast the best45;performing synthesizers in the domain of formal synthesis with precise logical specifications are still based on enumerative algorithms. In this paper we evaluate the abilities of LLMs to solve formal synthesis benchmarks by carefully crafting a library of prompts for the domain. When one45;shot synthesis fails we propose a novel enumerative synthesis algorithm which integrates calls to an LLM into a weighted probabilistic search. This allows the synthesizer to provide the LLM with information about the progress of the enumerator and the LLM to provide the enumerator with syntactic guidance in an iterative loop. We evaluate our techniques on benchmarks from the Syntax45;Guided Synthesis (SyGuS) competition. We find that GPT45;3.5 as a stand45;alone tool for formal synthesis is easily outperformed by state45;of45;the45;art formal synthesis algorithms but our approach integrating the LLM into an enumerative synthesis algorithm shows significant performance gains over both the LLM and the enumerative synthesizer alone and the winning SyGuS competition tool.
