---
layout: publication
title: 'Wisdom From Diversity: Bias Mitigation Through Hybrid Human-llm Crowds'
authors: Axel Abels, Tom Lenaerts
conference: "Arxiv"
year: 2025
bibkey: abels2025wisdom
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12349'}
tags: ['Ethics and Bias', 'RAG', 'Bias Mitigation']
---
Despite their performance, large language models (LLMs) can inadvertently perpetuate biases found in the data they are trained on. By analyzing LLM responses to bias-eliciting headlines, we find that these models often mirror human biases. To address this, we explore crowd-based strategies for mitigating bias through response aggregation. We first demonstrate that simply averaging responses from multiple LLMs, intended to leverage the "wisdom of the crowd", can exacerbate existing biases due to the limited diversity within LLM crowds. In contrast, we show that locally weighted aggregation methods more effectively leverage the wisdom of the LLM crowd, achieving both bias mitigation and improved accuracy. Finally, recognizing the complementary strengths of LLMs (accuracy) and humans (diversity), we demonstrate that hybrid crowds containing both significantly enhance performance and further reduce biases across ethnic and gender-related contexts.
