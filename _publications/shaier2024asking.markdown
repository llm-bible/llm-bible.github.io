---
layout: publication
title: 'Asking Again And Again: Exploring LLM Robustness To Repeated Questions'
authors: Sagi Shaier, Mario Sanz-guerrero, Katharina Von Der Wense
conference: "Arxiv"
year: 2024
bibkey: shaier2024asking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07923"}
tags: ['Security', 'GPT', 'Prompting', 'Model Architecture']
---
This study investigates whether repeating questions within prompts influences
the performance of large language models (LLMs). We hypothesize that
reiterating a question within a single prompt might enhance the model's focus
on key elements of the query. We evaluate five recent LLMs -- including
GPT-4o-mini, DeepSeek-V3, and smaller open-source models -- on three reading
comprehension datasets under different prompt settings, varying question
repetition levels (1, 3, or 5 times per prompt). Our results demonstrate that
question repetition can increase models' accuracy by up to \\(6%\\). However,
across all models, settings, and datasets, we do not find the result
statistically significant. These findings provide insights into prompt design
and LLM behavior, suggesting that repetition alone does not significantly
impact output quality.
