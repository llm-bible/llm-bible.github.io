---
layout: publication
title: 'Table-llm-specialist: Language Model Specialists For Tables Using Iterative Generator-validator Fine-tuning'
authors: Junjie Xing, Yeye He, Mengyu Zhou, Haoyu Dong, Shi Han, Dongmei Zhang, Surajit Chaudhuri
conference: "Arxiv"
year: 2024
bibkey: xing2024table
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12164"}
  - {name: "Code", url: "https://github.com/microsoft/Table-LLM-Specialist"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
In this work, we propose Table-LLM-Specialist, or Table-Specialist for short,
as a new self-trained fine-tuning paradigm specifically designed for table
tasks. Our insight is that for each table task, there often exist two dual
versions of the same task, one generative and one classification in nature.
Leveraging their duality, we propose a Generator-Validator paradigm, to
iteratively generate-then-validate training data from language-models, to
fine-tune stronger \sys models that can specialize in a given task, without
requiring manually-labeled data.
  Our extensive evaluations suggest that our Table-Specialist has (1)
\textit\{strong performance\} on diverse table tasks over vanilla language-models
-- for example, Table-Specialist fine-tuned on GPT-3.5 not only outperforms
vanilla GPT-3.5, but can often match or surpass GPT-4 level quality, (2)
\textit\{lower cost\} to deploy, because when Table-Specialist fine-tuned on
GPT-3.5 achieve GPT-4 level quality, it becomes possible to deploy smaller
models with lower latency and inference cost, with comparable quality, and (3)
\textit\{better generalizability\} when evaluated across multiple benchmarks,
since \sys is fine-tuned on a broad range of training data systematically
generated from diverse real tables. Our code and data will be available at
https://github.com/microsoft/Table-LLM-Specialist.
