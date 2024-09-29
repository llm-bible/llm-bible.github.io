---
layout: publication
title: bench Extending Long Context Evaluation Beyond 100K Tokens
authors: Zhang Xinrong, Chen Yingfa, Hu Shengding, Xu Zihang, Chen Junhao, Hao Moo Khai, Han Xu, Thai Zhen Leng, Wang Shuo, Liu Zhiyuan, Sun Maosong
conference: ""
year: 2024
bibkey: zhang2024bench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13718"}
tags: ['Agentic', 'Applications', 'Ethics And Bias', 'RAG']
---
Processing and reasoning over long contexts is crucial for many practical applications of Large Language Models (LLMs) such as document comprehension and agent construction. Despite recent strides in making LLMs process contexts with more than 100K tokens there is currently a lack of a standardized benchmark to evaluate this long-context capability. Existing public benchmarks typically focus on contexts around 10K tokens limiting the assessment and comparison of LLMs in processing longer contexts. In this paper we propose ∞Bench the first LLM benchmark featuring an average data length surpassing 100K tokens. ∞Bench comprises synthetic and realistic tasks spanning diverse domains presented in both English and Chinese. The tasks in ∞Bench are designed to require well understanding of long dependencies in contexts and make simply retrieving a limited number of passages from contexts not sufficient for these tasks. In our experiments based on ∞Bench we evaluate the state-of-the-art proprietary and open-source LLMs tailored for processing long contexts. The results indicate that existing long context LLMs still require significant advancements to effectively process 100K+ context. We further present three intriguing analyses regarding the behavior of LLMs processing long context.
