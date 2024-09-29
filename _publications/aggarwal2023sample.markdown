---
layout: publication
title: Lets Sample Step By Step Adaptive-consistency For Efficient Reasoning And Coding With Llms
authors: Aggarwal Pranjal, Madaan Aman, Yang Yiming, Mausam
conference: "Arxiv"
year: 2023
bibkey: aggarwal2023sample
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11860"}
  - {name: "Code", url: "https://www.sample-step-by-step.info"}
tags: ['Applications', 'Has Code', 'RAG']
---
A popular approach for improving the correctness of output from large language models (LLMs) is Self-Consistency - poll the LLM multiple times and output the most frequent solution. Existing Self-Consistency techniques always generate a constant number of samples per question where a better approach will be to non-uniformly distribute the available budget based on the amount of agreement in the samples generated so far. In response we introduce Adaptive-Consistency a cost-efficient model-agnostic technique that dynamically adjusts the number of samples per question using a lightweight stopping criterion. Our experiments over 17 reasoning and code generation datasets and three LLMs demonstrate that Adaptive-Consistency reduces sample budget by up to 7.9 times with an average accuracy drop of less than 0.137;. Our code and data are available at https://www.sample-step-by-step.info
