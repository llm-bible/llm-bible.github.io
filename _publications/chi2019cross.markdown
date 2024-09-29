---
layout: publication
title: Cross45;lingual Natural Language Generation Via Pre45;training
authors: Chi Zewen, Dong Li, Wei Furu, Wang Wenhui, Mao Xian-ling, Huang Heyan
conference: "Arxiv"
year: 2019
bibkey: chi2019cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.10481"}
  - {name: "Code", url: "https://github.com/CZWin32768/xnlg"}
tags: ['Applications', 'Has Code', 'RAG', 'Training Techniques']
---
In this work we focus on transferring supervision signals of natural language generation (NLG) tasks between multiple languages. We propose to pretrain the encoder and the decoder of a sequence45;to45;sequence model under both monolingual and cross45;lingual settings. The pre45;training objective encourages the model to represent different languages in the shared space so that we can conduct zero45;shot cross45;lingual transfer. After the pre45;training procedure we use monolingual data to fine45;tune the pre45;trained model on downstream NLG tasks. Then the sequence45;to45;sequence model trained in a single language can be directly evaluated beyond that language (i.e. accepting multi45;lingual input and producing multi45;lingual output). Experimental results on question generation and abstractive summarization show that our model outperforms the machine45;translation45;based pipeline methods for zero45;shot cross45;lingual generation. Moreover cross45;lingual transfer improves NLG performance of low45;resource languages by leveraging rich45;resource language data. Our implementation and data are available at https://github.com/CZWin32768/xnlg.
