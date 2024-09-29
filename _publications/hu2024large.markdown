---
layout: publication
title: Gentranslate Large Language Models Are Generative Multilingual Speech And Machine Translators
authors: Hu Yuchen, Chen Chen, Yang Chao-han Huck, Li Ruizhe, Zhang Dong, Chen Zhehuai, Chng Eng Siong
conference: "Arxiv"
year: 2024
bibkey: hu2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06894"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
Recent advances in large language models (LLMs) have stepped forward the development of multilingual speech and machine translation by its reduced representation errors and incorporated external knowledge. However both translation tasks typically utilize beam search decoding and top45;1 hypothesis selection for inference. These techniques struggle to fully exploit the rich information in the diverse N45;best hypotheses making them less optimal for translation tasks that require a single high45;quality output sequence. In this paper we propose a new generative paradigm for translation tasks namely GenTranslate which builds upon LLMs to generate better results from the diverse translation versions in N45;best list. Leveraging the rich linguistic knowledge and strong reasoning abilities of LLMs our new paradigm can integrate the rich information in N45;best candidates to generate a higher45;quality translation result. Furthermore to support LLM finetuning we build and release a HypoTranslate dataset that contains over 592K hypotheses45;translation pairs in 11 languages. Experiments on various speech and machine translation benchmarks (e.g. FLEURS CoVoST45;2 WMT) demonstrate that our GenTranslate significantly outperforms the state45;of45;the45;art model.
