---
layout: publication
title: 'Improving Pinterest Search Relevance Using Large Language Models'
authors: Han Wang, Mukuntha Narayanan Sundararaman, Onur Gungor, Yu Xu, Krishna Kamath, Rakesh Chalasani, Kurchi Subhra Hazra, Jinfeng Rao
conference: "Arxiv"
year: 2024
bibkey: wang2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17152'}
tags: ['Training Techniques', 'RAG', 'Model Architecture']
---
To improve relevance scoring on Pinterest Search, we integrate Large Language
Models (LLMs) into our search relevance model, leveraging carefully designed
text representations to predict the relevance of Pins effectively. Our approach
uses search queries alongside content representations that include captions
extracted from a generative visual language model. These are further enriched
with link-based text data, historically high-quality engaged queries,
user-curated boards, Pin titles and Pin descriptions, creating robust models
for predicting search relevance. We use a semi-supervised learning approach to
efficiently scale up the amount of training data, expanding beyond the
expensive human labeled data available. By utilizing multilingual LLMs, our
system extends training data to include unseen languages and domains, despite
initial data and annotator expertise being confined to English. Furthermore, we
distill from the LLM-based model into real-time servable model architectures
and features. We provide comprehensive offline experimental validation for our
proposed techniques and demonstrate the gains achieved through the final
deployed system at scale.
