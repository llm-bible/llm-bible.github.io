---
layout: publication
title: 'Finesure: Fine-grained Summarization Evaluation Using Llms'
authors: Hwanjun Song, Hang Su, Igor Shalyminov, Jason Cai, Saab Mansour
conference: "Arxiv"
year: 2024
bibkey: song2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00908"}
  - {name: "Code", url: "https://github.com/DISL-Lab/FineSurE-ACL24"}
tags: ['ACL', 'Has Code', 'Applications']
---
Automated evaluation is crucial for streamlining text summarization
benchmarking and model development, given the costly and time-consuming nature
of human evaluation. Traditional methods like ROUGE do not correlate well with
human judgment, while recently proposed LLM-based metrics provide only
summary-level assessment using Likert-scale scores. This limits deeper model
analysis, e.g., we can only assign one hallucination score at the summary
level, while at the sentence level, we can count sentences containing
hallucinations. To remedy those limitations, we propose FineSurE, a
fine-grained evaluator specifically tailored for the summarization task using
large language models (LLMs). It also employs completeness and conciseness
criteria, in addition to faithfulness, enabling multi-dimensional assessment.
We compare various open-source and proprietary LLMs as backbones for FineSurE.
In addition, we conduct extensive benchmarking of FineSurE against SOTA methods
including NLI-, QA-, and LLM-based methods, showing improved performance
especially on the completeness and conciseness dimensions. The code is
available at https://github.com/DISL-Lab/FineSurE-ACL24.
