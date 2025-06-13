---
layout: publication
title: 'Beyond No: Quantifying AI Over-refusal And Emotional Attachment Boundaries'
authors: David Noever, Grant Rosario
conference: "Arxiv"
year: 2025
bibkey: noever2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14975"}
tags: ['Tools', 'GPT', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Prompting']
---
We present an open-source benchmark and evaluation framework for assessing
emotional boundary handling in Large Language Models (LLMs). Using a dataset of
1156 prompts across six languages, we evaluated three leading LLMs (GPT-4o,
Claude-3.5 Sonnet, and Mistral-large) on their ability to maintain appropriate
emotional boundaries through pattern-matched response analysis. Our framework
quantifies responses across seven key patterns: direct refusal, apology,
explanation, deflection, acknowledgment, boundary setting, and emotional
awareness. Results demonstrate significant variation in boundary-handling
approaches, with Claude-3.5 achieving the highest overall score (8.69/10) and
producing longer, more nuanced responses (86.51 words on average). We
identified a substantial performance gap between English (average score 25.62)
and non-English interactions (< 0.22), with English responses showing markedly
higher refusal rates (43.20% vs. < 1% for non-English). Pattern analysis
revealed model-specific strategies, such as Mistral's preference for deflection
(4.2%) and consistently low empathy scores across all models (< 0.06).
Limitations include potential oversimplification through pattern matching, lack
of contextual understanding in response analysis, and binary classification of
complex emotional responses. Future work should explore more nuanced scoring
methods, expand language coverage, and investigate cultural variations in
emotional boundary expectations. Our benchmark and methodology provide a
foundation for systematic evaluation of LLM emotional intelligence and
boundary-setting capabilities.
