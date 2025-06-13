---
layout: publication
title: 'SAFE-SQL: Self-augmented In-context Learning With Fine-grained Example Selection For Text-to-sql'
authors: Jimin Lee, Ingeol Baek, Byeongjeong Kim, Hyunkyung Bae, Hwanhee Lee
conference: "Arxiv"
year: 2025
bibkey: lee2025safe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11438"}
tags: ['Tools', 'Reinforcement Learning', 'Training Techniques', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Text-to-SQL aims to convert natural language questions into executable SQL queries. While previous approaches, such as skeleton-masked selection, have demonstrated strong performance by retrieving similar training examples to guide large language models (LLMs), they struggle in real-world scenarios where such examples are unavailable. To overcome this limitation, we propose Self-Augmentation in-context learning with Fine-grained Example selection for Text-to-SQL (SAFE-SQL), a novel framework that improves SQL generation by generating and filtering self-augmented examples. SAFE-SQL first prompts an LLM to generate multiple Text-to-SQL examples relevant to the test input. Then SAFE-SQL filters these examples through three relevance assessments, constructing high-quality in-context learning examples. Using self-generated examples, SAFE-SQL surpasses the previous zero-shot, and few-shot Text-to-SQL frameworks, achieving higher execution accuracy. Notably, our approach provides additional performance gains in extra hard and unseen scenarios, where conventional methods often fail.
