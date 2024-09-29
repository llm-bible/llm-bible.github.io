---
layout: publication
title: 'Navigating The Labyrinth: Evaluating And Enhancing Llms'' Ability To Reason About Search Problems'
authors: Borazjanizadeh Nasim, Herzig Roei, Darrell Trevor, Feris Rogerio, Karlinsky Leonid
conference: "Arxiv"
year: 2024
bibkey: borazjanizadeh2024navigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12172"}
tags: ['GPT', 'In Context Learning', 'Model Architecture', 'Prompting']
---
Recently Large Language Models (LLMs) attained impressive performance in math and reasoning benchmarks. However they still often struggle with logic problems and puzzles that are relatively easy for humans. To further investigate this we introduce a new benchmark SearchBench containing 11 unique search problem types each equipped with automated pipelines to generate an arbitrary number of instances and analyze the feasibility correctness and optimality of LLM-generated solutions. We show that even the most advanced LLMs fail to solve these problems end-to-end in text e.g. GPT4 solves only 1.437;. SearchBench problems require considering multiple pathways to the solution as well as backtracking posing a significant challenge to auto-regressive models. Instructing LLMs to generate code that solves the problem helps but only slightly e.g. GPT4s performance rises to 11.737;. In this work we show that in-context learning with A algorithm implementations enhances performance. The full potential of this promoting approach emerges when combined with our proposed Multi-Stage-Multi-Try method which breaks down the algorithm implementation into two stages and verifies the first stage against unit tests raising GPT-4s performance above 5737;.
