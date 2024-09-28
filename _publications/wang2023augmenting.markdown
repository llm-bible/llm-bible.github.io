---
layout: publication
title: Augmenting Black-box LLMs with Medical Textbooks for Clinical Question Answering
authors: Wang Yubo, Ma Xueguang, Chen Wenhu
conference: "Arxiv"
year: 2023
bibkey: wang2023augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02233"}
tags: ['ARXIV', 'Applications', 'GPT', 'Tools']
---
Large-scale language models (LLMs) like ChatGPT have demonstrated impressive abilities in generating responses based on human instructions. However their use in the medical field can be challenging due to their lack of specific in-depth knowledge. In this study we present a system called LLMs Augmented with Medical Textbooks (LLM-AMT) designed to enhance the proficiency of LLMs in specialized domains. LLM-AMT integrates authoritative medical textbooks into the LLMs framework using plug-and-play modules. These modules include a Query Augmenter a Hybrid Textbook Retriever and a Knowledge Self-Refiner. Together they incorporate authoritative medical knowledge. Additionally an LLM Reader aids in contextual understanding. Our experimental results on three medical QA tasks demonstrate that LLMAMT significantly improves response quality with accuracy gains ranging from 11.6 to 16.6. Notably with GPT-4-Turbo as the base model LLM-AMT outperforms the specialized Med-PaLM 2 model pre-trained on a massive amount of medical corpus by 2-3. We found that despite being 100x smaller in size medical textbooks as a retrieval corpus is proven to be a more effective knowledge database than Wikipedia in the medical domain boosting performance by 7.8-13.7.
