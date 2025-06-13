---
layout: publication
title: 'Multi-granularity Hierarchical Attention Fusion Networks For Reading Comprehension And Question Answering'
authors: Wei Wang, Ming Yan, Chen Wu
conference: "Arxiv"
year: 2018
bibkey: wang2018multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1811.11934"}
tags: ['Model Architecture', 'RAG', 'Merging', 'Applications', 'Attention Mechanism']
---
This paper describes a novel hierarchical attention network for reading
comprehension style question answering, which aims to answer questions for a
given narrative paragraph. In the proposed method, attention and fusion are
conducted horizontally and vertically across layers at different levels of
granularity between question and paragraph. Specifically, it first encode the
question and paragraph with fine-grained language embeddings, to better capture
the respective representations at semantic level. Then it proposes a
multi-granularity fusion approach to fully fuse information from both global
and attended representations. Finally, it introduces a hierarchical attention
network to focuses on the answer span progressively with multi-level
softalignment. Extensive experiments on the large-scale SQuAD and TriviaQA
datasets validate the effectiveness of the proposed method. At the time of
writing the paper (Jan. 12th 2018), our model achieves the first position on
the SQuAD leaderboard for both single and ensemble models. We also achieves
state-of-the-art results on TriviaQA, AddSent and AddOne-Sent datasets.
