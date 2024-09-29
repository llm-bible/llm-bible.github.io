---
layout: publication
title: Better Generalization With Semantic Ids A Case Study In Ranking For Recommendations
authors: Singh Anima, Vu Trung, Mehta Nikhil, Keshavan Raghunandan, Sathiamoorthy Maheswaran, Zheng Yilin, Hong Lichan, Heldt Lukasz, Wei Li, Tandon Devansh, Chi Ed H., Yi Xinyang
conference: "Arxiv"
year: 2023
bibkey: singh2023better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.08121"}
tags: ['Multimodal Models', 'Reinforcement Learning', 'Tokenization']
---
Randomly45;hashed item ids are used ubiquitously in recommendation models. However the learned representations from random hashing prevents generalization across similar items causing problems of learning unseen and long45;tail items especially when item corpus is large power45;law distributed and evolving dynamically. In this paper we propose using content45;derived features as a replacement for random ids. We show that simply replacing ID features with content45;based embeddings can cause a drop in quality due to reduced memorization capability. To strike a good balance of memorization and generalization we propose to use Semantic IDs 45;45; a compact discrete item representation learned from frozen content embeddings using RQ45;VAE that captures the hierarchy of concepts in items 45;45; as a replacement for random item ids. Similar to content embeddings the compactness of Semantic IDs poses a problem of easy adaption in recommendation models. We propose novel methods for adapting Semantic IDs in industry45;scale ranking models through hashing sub45;pieces of of the Semantic45;ID sequences. In particular we find that the SentencePiece model that is commonly used in LLM tokenization outperforms manually crafted pieces such as N45;grams. To the end we evaluate our approaches in a real45;world ranking model for YouTube recommendations. Our experiments demonstrate that Semantic IDs can replace the direct use of video IDs by improving the generalization ability on new and long45;tail item slices without sacrificing overall model quality.
