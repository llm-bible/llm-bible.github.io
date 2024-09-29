---
layout: publication
title: PECC&#58; Problem Extraction And Coding Challenges
authors: Haller Patrick, Golde Jonas, Akbik Alan
conference: "Arxiv"
year: 2024
bibkey: haller2024problem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18766"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Recent advancements in large language models (LLMs) have showcased their exceptional abilities across various tasks such as code generation problem-solving and reasoning. Existing benchmarks evaluate tasks in isolation yet the extent to which LLMs can understand prose-style tasks identify the underlying problems and then generate appropriate code solutions is still unexplored. Addressing this gap we introduce PECC a novel benchmark derived from Advent Of Code (AoC) challenges and Project Euler including 2396 problems. Unlike conventional benchmarks PECC requires LLMs to interpret narrative-embedded problems extract requirements and generate executable code. A key feature of our dataset is the complexity added by natural language prompting in chat-based evaluations mirroring real-world instruction ambiguities. Results show varying model performance between narrative and neutral problems with specific challenges in the Euler math-based subset with GPT-3.5-Turbo passing 5037; of the AoC challenges and only 837; on the Euler problems. By probing the limits of LLMs capabilities our benchmark provides a framework to monitor and assess the subsequent progress of LLMs as a universal problem solver.
