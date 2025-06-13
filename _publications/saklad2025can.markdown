---
layout: publication
title: 'Can Large Language Models Infer Causal Relationships From Real-world Text?'
authors: Ryan Saklad, Aman Chadha, Oleg Pavlov, Raha Moraffah
conference: "Arxiv"
year: 2025
bibkey: saklad2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18931'}
tags: ['Reinforcement Learning', 'RAG']
---
Understanding and inferring causal relationships from texts is a core aspect of human cognition and is essential for advancing large language models (LLMs) towards artificial general intelligence. Existing work primarily focuses on synthetically generated texts which involve simple causal relationships explicitly mentioned in the text. This fails to reflect the complexities of real-world tasks. In this paper, we investigate whether LLMs are capable of inferring causal relationships from real-world texts. We develop a benchmark drawn from real-world academic literature which includes diverse texts with respect to length, complexity of relationships (different levels of explicitness, number of events, and causal relationships), and domains and sub-domains. To the best of our knowledge, our benchmark is the first-ever real-world dataset for this task. Our experiments on state-of-the-art LLMs evaluated on our proposed benchmark demonstrate significant challenges, with the best-performing model achieving an average F1 score of only 0.477. Analysis reveals common pitfalls: difficulty with implicitly stated information, in distinguishing relevant causal factors from surrounding contextual details, and with connecting causally relevant information spread across lengthy textual passages. By systematically characterizing these deficiencies, our benchmark offers targeted insights for further research into advancing LLM causal reasoning.
