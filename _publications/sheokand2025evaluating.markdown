---
layout: publication
title: 'Codemixbench: Evaluating Large Language Models On Code Generation With Code-mixed Prompts'
authors: Manik Sheokand, Parth Sawant
conference: "Arxiv"
year: 2025
bibkey: sheokand2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05063"}
tags: ['Tools', 'Applications', 'Reinforcement Learning', 'Security', 'Prompting']
---
Large Language Models (LLMs) have achieved remarkable success in code
generation tasks, powering various applications like code completion,
debugging, and programming assistance. However, existing benchmarks such as
HumanEval, MBPP, and BigCodeBench primarily evaluate LLMs on English-only
prompts, overlooking the real-world scenario where multilingual developers
often use code-mixed language while interacting with LLMs. To address this gap,
we introduce CodeMixBench, a novel benchmark designed to evaluate the
robustness of LLMs on code generation from code-mixed prompts. Built upon
BigCodeBench, CodeMixBench introduces controlled code-mixing (CMD) into the
natural language parts of prompts across three language pairs: Hinglish
(Hindi-English), Spanish-English, and Chinese Pinyin-English. We
comprehensively evaluate a diverse set of open-source code generation models
ranging from 1.5B to 15B parameters. Our results show that code-mixed prompts
consistently degrade Pass@1 performance compared to their English-only
counterparts, with performance drops increasing under higher CMD levels for
smaller models. CodeMixBench provides a realistic evaluation framework for
studying multilingual code generation and highlights new challenges and
directions for building robust code generation models that generalize well
across diverse linguistic settings.
