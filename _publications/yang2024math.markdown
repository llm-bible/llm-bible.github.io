---
layout: publication
title: 'Utmath: Math Evaluation With Unit Test Via Reasoning-to-coding Thoughts'
authors: Bo Yang, Qingping Yang, Yingwei Ma, Runtao Liu
conference: "Arxiv"
year: 2024
bibkey: yang2024math
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.07240"}
  - {name: "Code", url: "https://github.com/UTMathGroup/UTMath"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Has Code', 'Applications']
---
The evaluation of mathematical reasoning capabilities is essential for
advancing Artificial General Intelligence (AGI). While Large Language Models
(LLMs) have shown impressive performance in solving mathematical problems,
existing benchmarks such as GSM8K and MATH present limitations, including
narrow problem definitions with specific numbers and reliance on predetermined
rules that hinder accurate assessments of reasoning and generality. This paper
introduces the UTMath Benchmark, a robust evaluation framework designed to
assess LLMs through extensive unit tests, with a focus on both the accuracy and
generality of model responses. It comprises 1,053 cutting-edge problems
spanning nine mathematical domains, with an average of 68 test cases per
problem. UTMath is highly challenging, with the best-performing model, o1-mini,
solving only 32.57% of the problems, followed by o1-preview at 27.16%, and
GPT-4o at 26.93%. Furthermore, we present the Reasoning-to-Coding of Thoughts
(RCoT) approach, which encourages LLMs to engage in explicit reasoning prior to
code generation, thereby facilitating the production of more sophisticated
solutions and enhancing overall performance and efficiency. Additionally, we
also release the UTMath-Train training dataset (more than 70k samples), to
support the community in further exploring mathematical reasoning. Our
benchmark can be accessed via the following link:
https://github.com/UTMathGroup/UTMath
