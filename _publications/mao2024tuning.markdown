---
layout: publication
title: Tuning Llms With Contrastive Alignment Instructions For Machine Translation In Unseen Low45;resource Languages
authors: Mao Zhuoyuan, Yu Yen
conference: "Arxiv"
year: 2024
bibkey: mao2024tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05811"}
tags: ['Applications', 'Reinforcement Learning']
---
This article introduces contrastive alignment instructions (AlignInstruct) to address two challenges in machine translation (MT) on large language models (LLMs). One is the expansion of supported languages to previously unseen ones. The second relates to the lack of data in low45;resource languages. Model fine45;tuning through MT instructions (MTInstruct) is a straightforward approach to the first challenge. However MTInstruct is limited by weak cross45;lingual signals inherent in the second challenge. AlignInstruct emphasizes cross45;lingual supervision via a cross45;lingual discriminator built using statistical word alignments. Our results based on fine45;tuning the BLOOMZ models (1b1 3b and 7b1) in up to 24 unseen languages showed that (1) LLMs can effectively translate unseen languages using MTInstruct; (2) AlignInstruct led to consistent improvements in translation quality across 48 translation directions involving English; (3) Discriminator45;based instructions outperformed their generative counterparts as cross45;lingual instructions; (4) AlignInstruct improved performance in 30 zero45;shot directions.
