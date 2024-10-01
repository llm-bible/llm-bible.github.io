---
layout: publication
title: 'Speech-to-text Adapter And Speech-to-entity Retriever Augmented Llms For Speech Understanding'
authors: Wang Mingqiu, Shafran Izhak, Soltau Hagen, Han Wei, Cao Yuan, Yu Dian, Shafey Laurent El
conference: "Arxiv"
year: 2023
bibkey: wang2023speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.07944"}
tags: ['RAG']
---
'Large Language Models (LLMs) have been applied in the speech domain, often incurring a performance drop due to misaligned between speech and language representations. To bridge this gap, we propose a joint speech and language model (SLM) using a Speech2Text adapter, which maps speech into text token embedding space without speech information loss. Additionally, using a CTC-based blank-filtering, we can reduce the speech sequence length to that of text. In speech MultiWoz dataset (DSTC11 challenge), SLM largely improves the dialog state tracking (DST) performance (24.7&#37; to 28.4&#37; accuracy). Further to address errors on rare entities, we augment SLM with a Speech2Entity retriever, which uses speech to retrieve relevant entities, and then adds them to the original SLM input as a prefix. With this retrieval-augmented SLM (ReSLM), the DST performance jumps to 34.6&#37; accuracy. Moreover, augmenting the ASR task with the dialog understanding task improves the ASR performance from 9.4&#37; to 8.5&#37; WER.'
