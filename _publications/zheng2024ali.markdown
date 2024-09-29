---
layout: publication
title: Ali45;agent Assessing Llms Alignment With Human Values Via Agent45;based Evaluation
authors: Zheng Jingnan, Wang Han, Zhang An, Nguyen Tai D., Sun Jun, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: zheng2024ali
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14125"}
  - {name: "Code", url: "https://github.com/SophieZheng998/ALI&#45;Agent.git"}
tags: ['Agentic', 'Applications', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) can elicit unintended and even harmful content when misaligned with human values posing severe risks to users and society. To mitigate these risks current evaluation benchmarks predominantly employ expert45;designed contextual scenarios to assess how well LLMs align with human values. However the labor45;intensive nature of these benchmarks limits their test scope hindering their ability to generalize to the extensive variety of open45;world use cases and identify rare but crucial long45;tail risks. Additionally these static tests fail to adapt to the rapid evolution of LLMs making it hard to evaluate timely alignment issues. To address these challenges we propose ALI45;Agent an evaluation framework that leverages the autonomous abilities of LLM45;powered agents to conduct in45;depth and adaptive alignment assessments. ALI45;Agent operates through two principal stages Emulation and Refinement. During the Emulation stage ALI45;Agent automates the generation of realistic test scenarios. In the Refinement stage it iteratively refines the scenarios to probe long45;tail risks. Specifically ALI45;Agent incorporates a memory module to guide test scenario generation a tool45;using module to reduce human labor in tasks such as evaluating feedback from target LLMs and an action module to refine tests. Extensive experiments across three aspects of human values45;45;stereotypes morality and legality45;45;demonstrate that ALI45;Agent as a general evaluation framework effectively identifies model misalignment. Systematic analysis also validates that the generated test scenarios represent meaningful use cases as well as integrate enhanced measures to probe long45;tail risks. Our code is available at https://github.com/SophieZheng998/ALI&#45;Agent.git
