---
layout: publication
title: 'Prompt Design Matters For Computational Social Science Tasks But In Unpredictable Ways'
authors: Atreja Shubham, Ashkinaze Joshua, Li Lingyao, Mendelsohn Julia, Hemphill Libby
conference: "Arxiv"
year: 2024
bibkey: atreja2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11980"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting']
---
Manually annotating data for computational social science tasks can be costly, time-consuming, and emotionally draining. While recent work suggests that LLMs can perform such annotation tasks in zero-shot settings, little is known about how prompt design impacts LLMs' compliance and accuracy. We conduct a large-scale multi-prompt experiment to test how model selection (ChatGPT, PaLM2, and Falcon7b) and prompt design features (definition inclusion, output type, explanation, and prompt length) impact the compliance and accuracy of LLM-generated annotations on four CSS tasks (toxicity, sentiment, rumor stance, and news frames). Our results show that LLM compliance and accuracy are highly prompt-dependent. For instance, prompting for numerical scores instead of labels reduces all LLMs' compliance and accuracy. The overall best prompting setup is task-dependent, and minor prompt changes can cause large changes in the distribution of generated labels. By showing that prompt design significantly impacts the quality and distribution of LLM-generated annotations, this work serves as both a warning and practical guide for researchers and practitioners.
