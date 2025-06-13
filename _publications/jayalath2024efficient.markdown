---
layout: publication
title: 'PRISM: Efficient Long-range Reasoning With Short-context Llms'
authors: Dulhan Jayalath, James Bradley Wendt, Nicholas Monath, Sandeep Tata, Beliz Gunel
conference: "Arxiv"
year: 2024
bibkey: jayalath2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18914"}
tags: ['RAG', 'Training Techniques']
---
Long-range tasks demand reasoning over long inputs. Current solutions require
large compute budgets, training data, model weight access, or complex
task-specific designs. We introduce PRISM, which processes information as a
stream of chunks while maintaining a structured in-context memory specified
with a typed hierarchical schema. PRISM outperforms baselines on diverse tasks
while using at least 4x shorter contexts than long-context models. This
approach is token-efficient, producing concise outputs and efficiently
leveraging key-value (KV) caches to reduce costs by up to 54% compared to
alternative short-context methods. PRISM scales down to tiny chunks (<500
tokens) without increasing encoding costs or sacrificing quality, and
generalizes to new tasks with minimal effort by automatically generating
schemas from task descriptions.
