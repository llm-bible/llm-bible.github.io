---
layout: publication
title: Pybench Evaluating LLM Agent On Various Real-world Coding Tasks
authors: Zhang Yaolun, Pan Yinxu, Wang Yudong, Cai Jie
conference: "Arxiv"
year: 2024
bibkey: zhang2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16732"}
  - {name: "Code", url: "https://github.com/Mercury7353/PyBench"}
tags: ['Agentic', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The LLM Agent equipped with a code interpreter is capable of automatically solving real-world coding tasks such as data analysis and image editing. However existing benchmarks primarily focus on either simplistic tasks such as completing a few lines of code or on extremely complex and specific tasks at the repository level neither of which are representative of various daily coding tasks. To address this gap we introduce (textbfPyBench) a benchmark encompassing five main categories of real-world tasks covering more than 10 types of files. Given a high-level user query and related files the LLM Agent needs to reason and execute Python code via a code interpreter for a few turns before making a formal response to fulfill the users requirements. Successfully addressing tasks in PyBench demands a robust understanding of various Python packages superior reasoning capabilities and the ability to incorporate feedback from executed code. Our evaluations indicate that current open-source LLMs are struggling with these tasks. Hence we conduct analysis and experiments on four kinds of datasets proving that comprehensive abilities are needed for PyBench. Our fine-tuned 8B size model (textbfPyLlama3) achieves an exciting performance on PyBench which surpasses many 33B and 70B size models. Our Benchmark Training Dataset and Model are available at https://github.com/Mercury7353/PyBench\}
