---
layout: publication
title: 'Makieval: A Multilingual Automatic Wikidata-based Framework For Cultural Awareness Evaluation For Llms'
authors: Raoyuan Zhao, Beiduo Chen, Barbara Plank, Michael A. Hedderich
conference: "Arxiv"
year: 2025
bibkey: zhao2025multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21693'}
tags: ['Language Modeling', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Large language models (LLMs) are used globally across many languages, but their English-centric pretraining raises concerns about cross-lingual disparities for cultural awareness, often resulting in biased outputs. However, comprehensive multilingual evaluation remains challenging due to limited benchmarks and questionable translation quality. To better assess these disparities, we introduce MAKIEval, an automatic multilingual framework for evaluating cultural awareness in LLMs across languages, regions, and topics. MAKIEval evaluates open-ended text generation, capturing how models express culturally grounded knowledge in natural language. Leveraging Wikidata's multilingual structure as a cross-lingual anchor, it automatically identifies cultural entities in model outputs and links them to structured knowledge, enabling scalable, language-agnostic evaluation without manual annotation or translation. We then introduce four metrics that capture complementary dimensions of cultural awareness: granularity, diversity, cultural specificity, and consensus across languages. We assess 7 LLMs developed from different parts of the world, encompassing both open-source and proprietary systems, across 13 languages, 19 countries and regions, and 6 culturally salient topics (e.g., food, clothing). Notably, we find that models tend to exhibit stronger cultural awareness in English, suggesting that English prompts more effectively activate culturally grounded knowledge. We publicly release our code and data.
