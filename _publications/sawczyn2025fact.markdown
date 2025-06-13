---
layout: publication
title: 'Factselfcheck: Fact-level Black-box Hallucination Detection For Llms'
authors: Albert Sawczyn, Jakub Binkowski, Denis Janiak, Bogdan Gabrys, Tomasz Kajdanowicz
conference: "Arxiv"
year: 2025
bibkey: sawczyn2025fact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17229"}
tags: ['Training Techniques', 'GPT', 'Applications', 'Model Architecture']
---
Large Language Models (LLMs) frequently generate hallucinated content, posing significant challenges for applications where factuality is crucial. While existing hallucination detection methods typically operate at the sentence level or passage level, we propose FactSelfCheck, a novel black-box sampling-based method that enables fine-grained fact-level detection. Our approach represents text as knowledge graphs consisting of facts in the form of triples. Through analyzing factual consistency across multiple LLM responses, we compute fine-grained hallucination scores without requiring external resources or training data. Our evaluation demonstrates that FactSelfCheck performs competitively with leading sentence-level sampling-based methods while providing more detailed insights. Most notably, our fact-level approach significantly improves hallucination correction, achieving a 35.5% increase in factual content compared to the baseline, while sentence-level SelfCheckGPT yields only a 10.6% improvement. The granular nature of our detection enables more precise identification and correction of hallucinated content. Additionally, we contribute a new dataset for evaluating sampling-based methods - FavaMultiSamples.
