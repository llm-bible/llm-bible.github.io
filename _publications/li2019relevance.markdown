---
layout: publication
title: Relevance-promoting Language Model For Short-text Conversation
authors: Li Xin, Li Piji, Bi Wei, Liu Xiaojiang, Lam Wai
conference: "Arxiv"
year: 2019
bibkey: li2019relevance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.11489"}
  - {name: "Code", url: "https://ai.tencent.com/ailab/nlp/dialogue/"}
tags: ['Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Despite the effectiveness of sequence-to-sequence framework on the task of Short-Text Conversation (STC) the issue of under-exploitation of training data (i.e. the supervision signals from query text is (textitignored)) still remains unresolved. Also the adopted (textitmaximization)-based decoding strategies inclined to generating the generic responses or responses with repetition are unsuited to the STC task. In this paper we propose to formulate the STC task as a language modeling problem and tailor-make a training strategy to adapt a language model for response generation. To enhance generation performance we design a relevance-promoting transformer language model which performs additional supervised source attention after the self-attention to increase the importance of informative query tokens in calculating the token-level representation. The model further refines the query representation with relevance clues inferred from its multiple references during training. In testing we adopt a (textit)randomization-over-maximization strategy to reduce the generation of generic responses. Experimental results on a large Chinese STC dataset demonstrate the superiority of the proposed model on relevance metrics and diversity metrics.(footnote)Code available at https://ai.tencent.com/ailab/nlp/dialogue/.
