---
layout: publication
title: LCS A Language Converter Strategy For Zero45;shot Neural Machine Translation
authors: Sun Zengkui, Liu Yijin, Meng Fandong, Xu Jinan, Chen Yufeng, Zhou Jie
conference: "Arxiv"
year: 2024
bibkey: sun2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02876"}
tags: ['Applications', 'Merging', 'Tools']
---
Multilingual neural machine translation models generally distinguish translation directions by the language tag (LT) in front of the source or target sentences. However current LT strategies cannot indicate the desired target language as expected on zero45;shot translation i.e. the off45;target issue. Our analysis reveals that the indication of the target language is sensitive to the placement of the target LT. For example when placing the target LT on the decoder side the indication would rapidly degrade along with decoding steps while placing the target LT on the encoder side would lead to copying or paraphrasing the source input. To address the above issues we propose a simple yet effective strategy named Language Converter Strategy (LCS). By introducing the target language embedding into the top encoder layers LCS mitigates confusion in the encoder and ensures stable language indication for the decoder. Experimental results on MultiUN TED and OPUS45;100 datasets demonstrate that LCS could significantly mitigate the off45;target issue with language accuracy up to 95.2837; 96.2137; and 85.3537; meanwhile outperforming the vanilla LT strategy by 3.07 33 and 7.93 BLEU scores on zero45;shot translation respectively.
