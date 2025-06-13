---
layout: publication
title: 'Beyond Factual Accuracy: Evaluating Coverage Of Diverse Factual Information In Long-form Text Generation'
authors: Chris Samarinas, Alexander Krubner, Alireza Salemi, Youngwoo Kim, Hamed Zamani
conference: "Arxiv"
year: 2025
bibkey: samarinas2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03545"}
tags: ['Language Modeling', 'RAG', 'Applications', 'Tools']
---
This paper presents ICAT, an evaluation framework for measuring coverage of diverse factual information in long-form text generation. ICAT breaks down a long output text into a list of atomic claims and not only verifies each claim through retrieval from a (reliable) knowledge source, but also computes the alignment between the atomic factual claims and various aspects expected to be presented in the output. We study three implementations of the ICAT framework, each with a different assumption on the availability of aspects and alignment method. By adopting data from the diversification task in the TREC Web Track and the ClueWeb corpus, we evaluate the ICAT framework. We demonstrate strong correlation with human judgments and provide comprehensive evaluation across multiple state-of-the-art LLMs. Our framework further offers interpretable and fine-grained analysis of diversity and coverage. Its modular design allows for easy adaptation to different domains and datasets, making it a valuable tool for evaluating the qualitative aspects of long-form responses produced by LLMs.
