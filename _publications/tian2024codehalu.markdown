---
layout: publication
title: Codehalu Investigating Code Hallucinations In Llms Via Execution-based Verification
authors: Tian Yuchen, Yan Weixiang, Yang Qian, Zhao Xuandong, Chen Qian, Wang Wen, Luo Ziyang, Ma Lei, Song Dawn
conference: "Arxiv"
year: 2024
bibkey: tian2024codehalu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00253"}
  - {name: "Code", url: "https://github.com/yuchen814/CodeHalu"}
tags: ['Applications', 'Has Code', 'Reinforcement Learning']
---
Large Language Models (LLMs) have made significant progress in code generation offering developers groundbreaking automated programming support. However LLMs often generate code that is syntactically correct and even semantically plausible but may not execute as expected or fulfill specified requirements. This phenomenon of hallucinations in the code domain has not been systematically explored. To advance the communitys understanding and research on this issue we introduce the concept of code hallucinations and propose a classification method for code hallucination based on execution verification. We categorize code hallucinations into four main types mapping naming resource and logic hallucinations with each category further divided into different subcategories to understand and address the unique challenges faced by LLMs in code generation with finer granularity. Additionally we present a dynamic detection algorithm called CodeHalu designed to detect and quantify code hallucinations. We also introduce the CodeHaluEval benchmark which includes 8883 samples from 699 tasks to systematically and quantitatively evaluate code hallucinations. By evaluating 17 popular LLMs using this benchmark we reveal significant differences in their accuracy and reliability in code generation offering detailed insights for further improving the code generation capabilities of LLMs. The CodeHalu benchmark and code are publicly available at https://github.com/yuchen814/CodeHalu.
