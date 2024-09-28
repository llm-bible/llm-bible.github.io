---
layout: publication
title: Tuning LLMs with Contrastive Alignment Instructions for Machine Translation in Unseen Low-resource Languages
authors: Mao Zhuoyuan, Yu Yen
conference: "Arxiv"
year: 2024
bibkey: mao2024tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05811"}
tags: ['Pretraining Methods', 'Arxiv']
---
This article introduces contrastive alignment instructions (AlignInstruct) to address two challenges in machine translation (MT) on large language models (LLMs). One is the expansion of supported languages to previously unseen ones. The second relates to the lack of data in low-resource languages. Model fine-tuning through MT instructions (MTInstruct) is a straightforward approach to the first challenge. However MTInstruct is limited by weak cross-lingual signals inherent in the second challenge. AlignInstruct emphasizes cross-lingual supervision via a cross-lingual discriminator built using statistical word alignments. Our results based on fine-tuning the BLOOMZ models (1b1 3b and 7b1) in up to 24 unseen languages showed that (1) LLMs can effectively translate unseen languages using MTInstruct; (2) AlignInstruct led to consistent improvements in translation quality across 48 translation directions involving English; (3) Discriminator-based instructions outperformed their generative counterparts as cross-lingual instructions; (4) AlignInstruct improved performance in 30 zero-shot directions.
