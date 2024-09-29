---
layout: publication
title: Leveraging Knowledge In Multilingual Commonsense Reasoning
authors: Fang Yuwei, Wang Shuohang, Xu Yichong, Xu Ruochen, Sun Siqi, Zhu Chenguang, Zeng Michael
conference: "Arxiv"
year: 2021
bibkey: fang2021leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08462"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Commonsense reasoning (CSR) requires the model to be equipped with general world knowledge. While CSR is a language45;agnostic process most comprehensive knowledge sources are in few popular languages especially English. Thus it remains unclear how to effectively conduct multilingual commonsense reasoning (XCSR) for various languages. In this work we propose to utilize English knowledge sources via a translate45;retrieve45;translate (TRT) strategy. For multilingual commonsense questions and choices we collect related knowledge via translation and retrieval from the knowledge sources. The retrieved knowledge is then translated into the target language and integrated into a pre45;trained multilingual language model via visible knowledge attention. Then we utilize a diverse of 4 English knowledge sources to provide more comprehensive coverage of knowledge in different formats. Extensive results on the XCSR benchmark demonstrate that TRT with external knowledge can significantly improve multilingual commonsense reasoning in both zero45;shot and translate45;train settings outperforming 3.3 and 3.6 points over the previous state45;of45;the45;art on XCSR benchmark datasets (X45;CSQA and X45;CODAH).
