---
layout: publication
title: PBNR\: Prompt-based News Recommender System
authors: Li Xinyi, Zhang Yongfeng, Malthouse Edward C.
conference: "Arxiv"
year: 2023
bibkey: li2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07862"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Online news platforms often use personalized news recommendation methods to help users discover articles that align with their interests. These methods typically predict a matching score between a user and a candidate article to reflect the users preference for the article. Some previous works have used language model techniques such as the attention mechanism to capture users interests based on their past behaviors and to understand the content of articles. However these existing model architectures require adjustments if additional information is taken into account. Pre-trained large language models which can better capture word relationships and comprehend contexts have seen a significant development in recent years and these pre-trained models have the advantages of transfer learning and reducing the training time for downstream tasks. Meanwhile prompt learning is a newly developed technique that leverages pre-trained language models by building task-specific guidance for output generations. To leverage textual information in news articles this paper introduces the pre-trained large language model and prompt-learning to the community of news recommendation. The proposed model prompt-based news recommendation (PBNR) treats the personalized news recommendation as a text-to-text language task and designs personalized prompts to adapt to the pre-trained language model -- text-to-text transfer transformer (T5). Experimental studies using the Microsoft News dataset show that PBNR is capable of making accurate recommendations by taking into account various lengths of past behaviors of different users. PBNR can also easily adapt to new information without changing the model architecture and the training objective. Additionally PBNR can make recommendations based on users specific requirements allowing human-computer interaction in the news recommendation field.
