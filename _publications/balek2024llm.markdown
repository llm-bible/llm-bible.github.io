---
layout: publication
title: 'Llm-based Feature Generation From Text For Interpretable Machine Learning'
authors: Vojtěch Balek, Lukáš Sýkora, Vilém Sklenák, Tomáš Kliegr
conference: "Arxiv"
year: 2024
bibkey: balek2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07132"}
tags: ['Interpretability and Explainability', 'BERT', 'Model Architecture']
---
Existing text representations such as embeddings and bag-of-words are not
suitable for rule learning due to their high dimensionality and absent or
questionable feature-level interpretability. This article explores whether
large language models (LLMs) could address this by extracting a small number of
interpretable features from text. We demonstrate this process on two datasets
(CORD-19 and M17+) containing several thousand scientific articles from
multiple disciplines and a target being a proxy for research impact. An
evaluation based on testing for the statistically significant correlation with
research impact has shown that LLama 2-generated features are semantically
meaningful. We consequently used these generated features in text
classification to predict the binary target variable representing the citation
rate for the CORD-19 dataset and the ordinal 5-class target representing an
expert-awarded grade in the M17+ dataset. Machine-learning models trained on
the LLM-generated features provided similar predictive performance to the
state-of-the-art embedding model SciBERT for scientific text. The LLM used only
62 features compared to 768 features in SciBERT embeddings, and these features
were directly interpretable, corresponding to notions such as article
methodological rigor, novelty, or grammatical correctness. As the final step,
we extract a small number of well-interpretable action rules. Consistently
competitive results obtained with the same LLM feature set across both
thematically diverse datasets show that this approach generalizes across
domains.
