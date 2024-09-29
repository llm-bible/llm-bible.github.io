---
layout: publication
title: Retrieval45;generation Alignment For End45;to45;end Task45;oriented Dialogue System
authors: Shen Weizhou, Gao Yingqi, Huang Canbin, Wan Fanqi, Quan Xiaojun, Bi Wei
conference: "Arxiv"
year: 2023
bibkey: shen2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08877"}
  - {name: "Code", url: "https://github.com/shenwzh3/MK&#45;TOD"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG']
---
Developing an efficient retriever to retrieve knowledge from a large45;scale knowledge base (KB) is critical for task45;oriented dialogue systems to effectively handle localized and specialized tasks. However widely used generative models such as T5 and ChatGPT often struggle to differentiate subtle differences among the retrieved KB records when generating responses resulting in suboptimal quality of generated responses. In this paper we propose the application of maximal marginal likelihood to train a perceptive retriever by utilizing signals from response generation for supervision. In addition our approach goes beyond considering solely retrieved entities and incorporates various meta knowledge to guide the generator thus improving the utilization of knowledge. We evaluate our approach on three task45;oriented dialogue datasets using T5 and ChatGPT as the backbone models. The results demonstrate that when combined with meta knowledge the response generator can effectively leverage high45;quality knowledge records from the retriever and enhance the quality of generated responses. The codes and models of this paper are available at https://github.com/shenwzh3/MK&#45;TOD.
