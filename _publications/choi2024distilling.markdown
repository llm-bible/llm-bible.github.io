---
layout: publication
title: 'Rradistill: Distilling Llms'' Passage Ranking Ability For Long-tail Queries Document Re-ranking On A Search Engine'
authors: Nayoung Choi, Youngjune Lee, Gyu-hwung Cho, Haeyu Jeong, Jungmin Kong, Saehun Kim, Keunchan Park, Sarah Cho, Inchang Jeong, Gyohee Nam, Sunghoon Han, Wonil Yang, Jaeho Choi
conference: "Arxiv"
year: 2024
bibkey: choi2024distilling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18097'}
tags: ['Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools']
---
Large Language Models (LLMs) excel at understanding the semantic
relationships between queries and documents, even with lengthy and complex
long-tail queries. These queries are challenging for feedback-based rankings
due to sparse user engagement and limited feedback, making LLMs' ranking
ability highly valuable. However, the large size and slow inference of LLMs
necessitate the development of smaller, more efficient models (sLLMs).
Recently, integrating ranking label generation into distillation techniques has
become crucial, but existing methods underutilize LLMs' capabilities and are
cumbersome. Our research, RRADistill: Re-Ranking Ability Distillation, propose
an efficient label generation pipeline and novel sLLM training methods for both
encoder and decoder models. We introduce an encoder-based method using a Term
Control Layer to capture term matching signals and a decoder-based model with a
ranking layer for enhanced understanding. A/B testing on a Korean-based search
platform, validates the effectiveness of our approach in improving re-ranking
for long-tail queries.
