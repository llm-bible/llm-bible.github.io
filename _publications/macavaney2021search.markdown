---
layout: publication
title: 'Intent5: Search Result Diversification Using Causal Language Models'
authors: Sean Macavaney, Craig Macdonald, Roderick Murray-smith, Iadh Ounis
conference: "Arxiv"
year: 2021
bibkey: macavaney2021search
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2108.04026'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Applications', 'Fine-Tuning', 'Pretraining Methods']
---
Search result diversification is a beneficial approach to overcome
under-specified queries, such as those that are ambiguous or multi-faceted.
Existing approaches often rely on massive query logs and interaction data to
generate a variety of possible query intents, which then can be used to re-rank
documents. However, relying on user interaction data is problematic because one
first needs a massive user base to build a sufficient log; public query logs
are insufficient on their own. Given the recent success of causal language
models (such as the Text-To-Text Transformer (T5) model) at text generation
tasks, we explore the capacity of these models to generate potential query
intents. We find that to encourage diversity in the generated queries, it is
beneficial to adapt the model by including a new Distributional Causal Language
Modeling (DCLM) objective during fine-tuning and a representation replacement
during inference. Across six standard evaluation benchmarks, we find that our
method (which we call IntenT5) improves search result diversity and attains
(and sometimes exceeds) the diversity obtained when using query suggestions
based on a proprietary query log. Our analysis shows that our approach is most
effective for multi-faceted queries and is able to generalize effectively to
queries that were unseen in training data.
