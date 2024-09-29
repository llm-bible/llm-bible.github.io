---
layout: publication
title: Relevance45;promoting Language Model For Short45;text Conversation
authors: Li Xin, Li Piji, Bi Wei, Liu Xiaojiang, Lam Wai
conference: "Arxiv"
year: 2019
bibkey: li2019relevance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.11489"}
  - {name: "Code", url: "https://ai.tencent.com/ailab/nlp/dialogue/"}
tags: ['Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Despite the effectiveness of sequence45;to45;sequence framework on the task of Short45;Text Conversation (STC) the issue of under45;exploitation of training data (i.e. the supervision signals from query text is textit123;ignored125;) still remains unresolved. Also the adopted textit123;maximization125;45;based decoding strategies inclined to generating the generic responses or responses with repetition are unsuited to the STC task. In this paper we propose to formulate the STC task as a language modeling problem and tailor45;make a training strategy to adapt a language model for response generation. To enhance generation performance we design a relevance45;promoting transformer language model which performs additional supervised source attention after the self45;attention to increase the importance of informative query tokens in calculating the token45;level representation. The model further refines the query representation with relevance clues inferred from its multiple references during training. In testing we adopt a textit123;randomization45;over45;maximization125; strategy to reduce the generation of generic responses. Experimental results on a large Chinese STC dataset demonstrate the superiority of the proposed model on relevance metrics and diversity metrics.footnote123;Code available at https://ai.tencent.com/ailab/nlp/dialogue/.
