---
layout: publication
title: 'Evaluation Of Llms-based Hidden States As Author Representations For Psychological Human-centered NLP Tasks'
authors: Nikita Soni, Pranav Chitale, Khushboo Singh, Niranjan Balasubramanian, H. Andrew Schwartz
conference: "Arxiv"
year: 2025
bibkey: soni2025evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00124"}
tags: ['Model Architecture', 'RAG', 'Transformer', 'Pretraining Methods']
---
Like most of NLP, models for human-centered NLP tasks -- tasks attempting to
assess author-level information -- predominantly use representations derived
from hidden states of Transformer-based LLMs. However, what component of the LM
is used for the representation varies widely. Moreover, there is a need for
Human Language Models (HuLMs) that implicitly model the author and provide a
user-level hidden state. Here, we systematically evaluate different ways of
representing documents and users using different LM and HuLM architectures to
predict task outcomes as both dynamically changing states and averaged
trait-like user-level attributes of valence, arousal, empathy, and distress. We
find that representing documents as an average of the token hidden states
performs the best generally. Further, while a user-level hidden state itself is
rarely the best representation, we find its inclusion in the model strengthens
token or document embeddings used to derive document- and user-level
representations resulting in best performances.
