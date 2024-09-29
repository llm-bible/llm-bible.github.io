---
layout: publication
title: LLM4SGG Large Language Models For Weakly Supervised Scene Graph Generation
authors: Kim Kibum, Yoon Kanghoon, Jeon Jaehyeong, In Yeonjun, Moon Jinyoung, Kim Donghyun, Park Chanyoung
conference: "CVPR"
year: 2023
bibkey: kim2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10404"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Weakly45;Supervised Scene Graph Generation (WSSGG) research has recently emerged as an alternative to the fully45;supervised approach that heavily relies on costly annotations. In this regard studies on WSSGG have utilized image captions to obtain unlocalized triplets while primarily focusing on grounding the unlocalized triplets over image regions. However they have overlooked the two issues involved in the triplet formation process from the captions 1) Semantic over45;simplification issue arises when extracting triplets from captions where fine45;grained predicates in captions are undesirably converted into coarse45;grained predicates resulting in a long45;tailed predicate distribution and 2) Low45;density scene graph issue arises when aligning the triplets in the caption with entity/predicate classes of interest where many triplets are discarded and not used in training leading to insufficient supervision. To tackle the two issues we propose a new approach i.e. Large Language Model for weakly45;supervised SGG (LLM4SGG) where we mitigate the two issues by leveraging the LLMs in45;depth understanding of language and reasoning ability during the extraction of triplets from captions and alignment of entity/predicate classes with target data. To further engage the LLM in these processes we adopt the idea of Chain45;of45;Thought and the in45;context few45;shot learning strategy. To validate the effectiveness of LLM4SGG we conduct extensive experiments on Visual Genome and GQA datasets showing significant improvements in both Recall35;64;K and mean Recall35;64;K compared to the state45;of45;the45;art WSSGG methods. A further appeal is that LLM4SGG is data45;efficient enabling effective model training with a small amount of training images.
