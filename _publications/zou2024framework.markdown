---
layout: publication
title: 'Telecomgpt: A Framework To Build Telecom-specfic Large Language Models'
authors: Hang Zou, Qiyang Zhao, Yu Tian, Lina Bariah, Faouzi Bader, Thierry Lestable, Merouane Debbah
conference: "Arxiv"
year: 2024
bibkey: zou2024framework
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.09424'}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Applications', 'GPT', 'Pre-Training']
---
Large Language Models (LLMs) have the potential to revolutionize the Sixth
Generation (6G) communication networks. However, current mainstream LLMs
generally lack the specialized knowledge in telecom domain. In this paper, for
the first time, we propose a pipeline to adapt any general purpose LLMs to a
telecom-specific LLMs. We collect and build telecom-specific pre-train dataset,
instruction dataset, preference dataset to perform continual pre-training,
instruct tuning and alignment tuning respectively. Besides, due to the lack of
widely accepted evaluation benchmarks in telecom domain, we extend existing
evaluation benchmarks and proposed three new benchmarks, namely, Telecom Math
Modeling, Telecom Open QnA and Telecom Code Tasks. These new benchmarks provide
a holistic evaluation of the capabilities of LLMs including math modeling,
Open-Ended question answering, code generation, infilling, summarization and
analysis in telecom domain. Our fine-tuned LLM TelecomGPT outperforms state of
the art (SOTA) LLMs including GPT-4, Llama-3 and Mistral in Telecom Math
Modeling benchmark significantly and achieve comparable performance in various
evaluation benchmarks such as TeleQnA, 3GPP technical documents classification,
telecom code summary and generation and infilling.
