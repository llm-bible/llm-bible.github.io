---
layout: publication
title: 'Enhancing Repository-level Code Generation With Integrated Contextual Information'
authors: Pan Zhiyuan, Hu Xing, Xia Xin, Yang Xiaohu
conference: "Arxiv"
year: 2024
bibkey: pan2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03283"}
tags: ['Applications', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
'Large language models (LLMs) have demonstrated remarkable capabilities in code generation tasks. However, repository-level code generation presents unique challenges, particularly due to the need to utilize information spread across multiple files within a repository. Existing retrieval-based approaches sometimes fall short as they are limited in obtaining a broader and deeper repository context. In this paper, we present CatCoder, a novel code generation framework designed for statically typed programming languages. CatCoder enhances repository-level code generation by integrating relevant code and type context. Specifically, it leverages static analyzers to extract type dependencies and merges this information with retrieved code to create comprehensive prompts for LLMs. To evaluate the effectiveness of CatCoder, we adapt and construct benchmarks that include 199 Java tasks and 90 Rust tasks. The results show that CatCoder outperforms the RepoCoder baseline by up to 17.35&#37;, in terms of pass@k score. Furthermore, the generalizability of CatCoder is assessed using various LLMs, including both code-specialized models and general-purpose models. Our findings indicate consistent performance improvements across all models, which underlines the practicality of CatCoder.'
