---
layout: publication
title: Fully Autonomous Programming With Large Language Models
authors: Liventsev Vadim, Grishina Anastasiia, Härmä Aki, Moonen Leon
conference: "Arxiv"
year: 2023
bibkey: liventsev2023fully
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.10423"}
tags: ['Pretraining Methods', 'Prompting', 'Tools']
---
Current approaches to program synthesis with Large Language Models (LLMs) exhibit a near miss syndrome they tend to generate programs that semantically resemble the correct answer (as measured by text similarity metrics or human evaluation) but achieve a low or even zero accuracy as measured by unit tests due to small imperfections such as the wrong input or output format. This calls for an approach known as Synthesize Execute Debug (SED) whereby a draft of the solution is generated first followed by a program repair phase addressing the failed tests. To effectively apply this approach to instruction45;driven LLMs one needs to determine which prompts perform best as instructions for LLMs as well as strike a balance between repairing unsuccessful programs and replacing them with newly generated ones. We explore these trade45;offs empirically comparing replace45;focused repair45;focused and hybrid debug strategies as well as different template45;based and model45;based prompt45;generation techniques. We use OpenAI Codex as the LLM and Program Synthesis Benchmark 2 as a database of problem descriptions and tests for evaluation. The resulting framework outperforms both conventional usage of Codex without the repair phase and traditional genetic programming approaches.
