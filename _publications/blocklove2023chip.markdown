---
layout: publication
title: Chip45;chat Challenges And Opportunities In Conversational Hardware Design
authors: Blocklove Jason, Garg Siddharth, Karri Ramesh, Pearce Hammond
conference: "Arxiv"
year: 2023
bibkey: blocklove2023chip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13243"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Modern hardware design starts with specifications provided in natural language. These are then translated by hardware engineers into appropriate Hardware Description Languages (HDLs) such as Verilog before synthesizing circuit elements. Automating this translation could reduce sources of human error from the engineering process. But it is only recently that artificial intelligence (AI) has demonstrated capabilities for machine45;based end45;to45;end design translations. Commercially45;available instruction45;tuned Large Language Models (LLMs) such as OpenAIs ChatGPT and Googles Bard claim to be able to produce code in a variety of programming languages; but studies examining them for hardware are still lacking. In this work we thus explore the challenges faced and opportunities presented when leveraging these recent advances in LLMs for hardware design. Given that these conversational LLMs perform best when used interactively we perform a case study where a hardware engineer co45;architects a novel 845;bit accumulator45;based microprocessor architecture with the LLM according to real45;world hardware constraints. We then sent the processor to tapeout in a Skywater 130nm shuttle meaning that this Chip45;Chat resulted in what we believe to be the worlds first wholly45;AI45;written HDL for tapeout.
