---
layout: publication
title: 'Who''s Who: Large Language Models Meet Knowledge Conflicts In Practice'
authors: Quang Hieu Pham, Hoang Ngo, Anh Tuan Luu, Dat Quoc Nguyen
conference: "Arxiv"
year: 2024
bibkey: pham2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15737"}
tags: ['RAG', 'Ethics and Bias']
---
Retrieval-augmented generation (RAG) methods are viable solutions for addressing the static memory limits of pre-trained language models. Nevertheless, encountering conflicting sources of information within the retrieval context is an inevitable practical challenge. In such situations, the language models are recommended to transparently inform users about the conflicts rather than autonomously deciding what to present based on their inherent biases. To analyze how current large language models (LLMs) align with our recommendation, we introduce WhoQA, a public benchmark dataset to examine model's behavior in knowledge conflict situations. We induce conflicts by asking about a common property among entities having the same name, resulting in questions with up to 8 distinctive answers. WhoQA evaluation set includes 5K questions across 13 Wikidata property types and 150K Wikipedia entities. Our experiments show that despite the simplicity of WhoQA questions, knowledge conflicts significantly degrades LLMs' performance in RAG settings.
