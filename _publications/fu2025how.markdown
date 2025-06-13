---
layout: publication
title: 'How Reliable Is Multilingual Llm-as-a-judge?'
authors: Xiyan Fu, Wei Liu
conference: "Arxiv"
year: 2025
bibkey: fu2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12201"}
tags: ['RAG', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
LLM-as-a-Judge has emerged as a popular evaluation strategy, where advanced large language models assess generation results in alignment with human instructions. While these models serve as a promising alternative to human annotators, their reliability in multilingual evaluation remains uncertain. To bridge this gap, we conduct a comprehensive analysis of multilingual LLM-as-a-Judge. Specifically, we evaluate five models from different model families across five diverse tasks involving 25 languages. Our findings reveal that LLMs struggle to achieve consistent judgment results across languages, with an average Fleiss' Kappa of approximately 0.3, and some models performing even worse. To investigate the cause of inconsistency, we analyze various influencing factors. We observe that consistency varies significantly across languages, with particularly poor performance in low-resource languages. Additionally, we find that neither training on multilingual data nor increasing model scale directly improves judgment consistency. These findings suggest that LLMs are not yet reliable for evaluating multilingual predictions. We finally propose an ensemble strategy which improves the consistency of the multilingual judge in real-world applications.
