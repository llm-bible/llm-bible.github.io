---
layout: publication
title: 'Learning To Explore And Select For Coverage-conditioned Retrieval-augmented Generation'
authors: Kim Takyoung, Lee Kyungjae, Jang Young Rok, Cho Ji Yong, Kim Gangwoo, Cho Minseok, Lee Moontae
conference: "Arxiv"
year: 2024
bibkey: kim2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01158"}
  - {name: "Code", url: "https://github.com/youngerous/qtree"}
tags: ['Has Code', 'RAG', 'Training Techniques']
---
"Interactions with billion-scale large language models typically yield long-form responses due to their extensive parametric capacities, along with retrieval-augmented features. While detailed responses provide insightful viewpoint of a specific subject, they frequently generate redundant and less engaging content that does not meet user interests. In this work, we focus on the role of query outlining (i.e., selected sequence of queries) in scenarios that users request a specific range of information, namely coverage-conditioned (\(C^2\)) scenarios. For simulating \(C^2\) scenarios, we construct QTree, 10K sets of information-seeking queries decomposed with various perspectives on certain topics. By utilizing QTree, we train QPlanner, a 7B language model generating customized query outlines that follow coverage-conditioned queries. We analyze the effectiveness of generated outlines through automatic and human evaluation, targeting on retrieval-augmented generation (RAG). Moreover, the experimental results demonstrate that QPlanner with alignment training can further provide outlines satisfying diverse user interests. Our resources are available at https://github.com/youngerous/qtree."
