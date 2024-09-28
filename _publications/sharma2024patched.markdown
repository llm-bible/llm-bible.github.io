---
layout: publication
title: Patched RTC evaluating LLMs for diverse software development tasks
authors: Sharma Asankhaya
conference: "Arxiv"
year: 2024
bibkey: sharma2024patched
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16557"}
tags: ['Survey Paper', 'Arxiv', 'LLM', 'GPT', 'Ethics and Bias']
---
This paper introduces Patched Round-Trip Correctness (Patched RTC) a novel evaluation technique for Large Language Models (LLMs) applied to diverse software development tasks particularly focusing on outer loop activities such as bug fixing code review and documentation updates. Patched RTC extends the original Round-Trip Correctness method to work with any LLM and downstream task offering a self-evaluating framework that measures consistency and robustness of model responses without human intervention. The study demonstrates a correlation between Patched RTC scores and task-specific accuracy metrics presenting it as an alternative to the LLM-as-Judge paradigm for open-domain task evaluation. We implement Patched RTC in an open-source framework called patchwork allowing for transparent evaluation during inference across various patchflows. Experiments comparing GPT-3.5 and GPT-4 models across different software development tasks reveal that Patched RTC effectively distinguishes model performance and task difficulty. The paper also explores the impact of consistency prompts on improving model accuracy suggesting that Patched RTC can guide prompt refinement and model selection for complex software development workflows.
