---
layout: publication
title: 'ZEBRA: Zero-shot Example-based Retrieval Augmentation For Commonsense Question Answering'
authors: Francesco Maria Molfese, Simone Conia, Riccardo Orlando, Roberto Navigli
conference: "Arxiv"
year: 2024
bibkey: molfese2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05077"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Interpretability and Explainability', 'Applications']
---
Current Large Language Models (LLMs) have shown strong reasoning capabilities
in commonsense question answering benchmarks, but the process underlying their
success remains largely opaque. As a consequence, recent approaches have
equipped LLMs with mechanisms for knowledge retrieval, reasoning and
introspection, not only to improve their capabilities but also to enhance the
interpretability of their outputs. However, these methods require additional
training, hand-crafted templates or human-written explanations. To address
these issues, we introduce ZEBRA, a zero-shot question answering framework that
combines retrieval, case-based reasoning and introspection and dispenses with
the need for additional training of the LLM. Given an input question, ZEBRA
retrieves relevant question-knowledge pairs from a knowledge base and generates
new knowledge by reasoning over the relationships in these pairs. This
generated knowledge is then used to answer the input question, improving the
model's performance and interpretability. We evaluate our approach across 8
well-established commonsense reasoning benchmarks, demonstrating that ZEBRA
consistently outperforms strong LLMs and previous knowledge integration
approaches, achieving an average accuracy improvement of up to 4.5 points.
