---
layout: publication
title: "Logical Reasoning For Task Oriented Dialogue Systems"
authors: Beygi Sajjad, Fazel-zarandi Maryam, Cervone Alessandra, Krishnan Prakash, Jonnalagadda Siddhartha Reddy
conference: "Arxiv"
year: 2022
bibkey: beygi2022logical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.04161"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
In recent years large pretrained models have been used in dialogue systems to improve successful task completion rates. However lack of reasoning capabilities of dialogue platforms make it difficult to provide relevant and fluent responses unless the designers of a conversational experience spend a considerable amount of time implementing these capabilities in external rule based modules. In this work we propose a novel method to fine-tune pretrained transformer models such as Roberta and T5. to reason over a set of facts in a given dialogue context. Our method includes a synthetic data generation mechanism which helps the model learn logical relations such as comparison between list of numerical values inverse relations (and negation) inclusion and exclusion for categorical attributes and application of a combination of attributes over both numerical and categorical values and spoken form for numerical values without need for additional training dataset. We show that the transformer based model can perform logical reasoning to answer questions when the dialogue context contains all the required information otherwise it is able to extract appropriate constraints to pass to downstream components (e.g. a knowledge base) when partial information is available. We observe that transformer based models such as UnifiedQA-T5 can be fine-tuned to perform logical reasoning (such as numerical and categorical attributes comparison) over attributes that been seen in training time (e.g. accuracy of 9037;+ for comparison of smaller than k_(max)=5 values over heldout test dataset).
