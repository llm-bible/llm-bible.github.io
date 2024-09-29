---
layout: publication
title: Improving Conversational Recommendation Systems Quality with Context-Aware Item Meta Information
authors: Yang Bowen, Han Cong, Li Yu, Zuo Lei, Yu Zhou
conference: "Arxiv"
year: 2021
bibkey: yang2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.08140"}
tags: ['Applications', 'Model Architecture']
---
Conversational recommendation systems (CRS) engage with users by inferring user preferences from dialog history providing accurate recommendations and generating appropriate responses. Previous CRSs use knowledge graph (KG) based recommendation modules and integrate KG with language models for response generation. Although KG-based approaches prove effective two issues remain to be solved. First KG-based approaches ignore the information in the conversational context but only rely on entity relations and bag of words to recommend items. Second it requires substantial engineering efforts to maintain KGs that model domain-specific relations thus leading to less flexibility. In this paper we propose a simple yet effective architecture comprising a pre-trained language model (PLM) and an item metadata encoder. The encoder learns to map item metadata to embeddings that can reflect the semantic information in the dialog context. The PLM then consumes the semantic-aligned item embeddings together with dialog context to generate high-quality recommendations and responses. Instead of modeling entity relations with KGs our model reduces engineering complexity by directly converting each item to an embedding. Experimental results on the benchmark dataset ReDial show that our model obtains state-of-the-art results on both recommendation and response generation tasks.
