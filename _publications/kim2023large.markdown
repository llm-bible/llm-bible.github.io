---
layout: publication
title: 'LLM4SGG: Large Language Models For Weakly Supervised Scene Graph Generation'
authors: Kim Kibum, Yoon Kanghoon, Jeon Jaehyeong, In Yeonjun, Moon Jinyoung, Kim Donghyun, Park Chanyoung
conference: "CVPR"
year: 2023
bibkey: kim2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10404"}
tags: ['Few Shot', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Uncategorized']
---
Weakly-Supervised Scene Graph Generation (WSSGG) research has recently
emerged as an alternative to the fully-supervised approach that heavily relies
on costly annotations. In this regard, studies on WSSGG have utilized image
captions to obtain unlocalized triplets while primarily focusing on grounding
the unlocalized triplets over image regions. However, they have overlooked the
two issues involved in the triplet formation process from the captions: 1)
Semantic over-simplification issue arises when extracting triplets from
captions, where fine-grained predicates in captions are undesirably converted
into coarse-grained predicates, resulting in a long-tailed predicate
distribution, and 2) Low-density scene graph issue arises when aligning the
triplets in the caption with entity/predicate classes of interest, where many
triplets are discarded and not used in training, leading to insufficient
supervision. To tackle the two issues, we propose a new approach, i.e., Large
Language Model for weakly-supervised SGG (LLM4SGG), where we mitigate the two
issues by leveraging the LLM's in-depth understanding of language and reasoning
ability during the extraction of triplets from captions and alignment of
entity/predicate classes with target data. To further engage the LLM in these
processes, we adopt the idea of Chain-of-Thought and the in-context few-shot
learning strategy. To validate the effectiveness of LLM4SGG, we conduct
extensive experiments on Visual Genome and GQA datasets, showing significant
improvements in both Recall@K and mean Recall@K compared to the
state-of-the-art WSSGG methods. A further appeal is that LLM4SGG is
data-efficient, enabling effective model training with a small amount of
training images.
