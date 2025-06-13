---
layout: publication
title: 'Codereviewqa: The Code Review Comprehension Assessment For Large Language Models'
authors: Hong Yi Lin, Chunhua Liu, Haoyu Gao, Patanamon Thongtanunam, Christoph Treude
conference: "Arxiv"
year: 2025
bibkey: lin2025code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16167"}
tags: ['Training Techniques', 'Survey Paper', 'Applications', 'Reinforcement Learning']
---
State-of-the-art large language models (LLMs) have demonstrated impressive code generation capabilities but struggle with real-world software engineering tasks, such as revising source code to address code reviews, hindering their practical use. Code review comments are often implicit, ambiguous, and colloquial, requiring models to grasp both code and human intent. This challenge calls for evaluating large language models' ability to bridge both technical and conversational contexts. While existing work has employed the automated code refinement (ACR) task to resolve these comments, current evaluation methods fall short, relying on text matching metrics that provide limited insight into model failures and remain susceptible to training data contamination. To address these limitations, we introduce a novel evaluation benchmark, \\(\textbf\{CodeReviewQA\}\\) that enables us to conduct fine-grained assessment of model capabilities and mitigate data contamination risks. In CodeReviewQA, we decompose the generation task of code refinement into \\(\textbf\{three essential reasoning steps\}\\): \\(\textit\{change type recognition\}\\) (CTR), \\(\textit\{change localisation\}\\) (CL), and \\(\textit\{solution identification\}\\) (SI). Each step is reformulated as multiple-choice questions with varied difficulty levels, enabling precise assessment of model capabilities, while mitigating data contamination risks. Our comprehensive evaluation spans 72 recently released large language models on \\(\textbf\{900 manually curated, high-quality examples\}\\) across nine programming languages. Our results show that CodeReviewQA is able to expose specific model weaknesses in code review comprehension, disentangled from their generative automated code refinement results.
