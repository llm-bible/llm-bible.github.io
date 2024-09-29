---
layout: publication
title: Lobass Gauging Learnability In Supervised Fine45;tuning Data
authors: Zhou Haotian, Liu Tingkai, Ma Qianli, Yuan Jianbo, Liu Pengfei, You Yang, Yang Hongxia
conference: "Arxiv"
year: 2023
bibkey: zhou2023gauging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13008"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Supervised Fine45;Tuning (SFT) serves as a crucial phase in aligning Large Language Models (LLMs) to specific task prerequisites. The selection of fine45;tuning data profoundly influences the models performance whose principle is traditionally grounded in data quality and distribution. In this paper we introduce a new dimension in SFT data selection learnability. This new dimension is motivated by the intuition that SFT unlocks capabilities acquired by a LLM during the pretraining phase. Given that different pretrained models have disparate capabilities the SFT data appropriate for one may not suit another. Thus we introduce the term learnability to define the suitability of data for effective learning by the model. We present the Loss Based SFT Data Selection (LoBaSS) method utilizing data learnability as the principal criterion for the selection SFT data. This method provides a nuanced approach allowing the alignment of data selection with inherent model capabilities ensuring optimal compatibility and learning efficiency. In experimental comparisons involving 7B and 13B models our LoBaSS method is able to surpass full45;data fine45;tuning at merely 637; of the total training data. When employing 16.737; of the data LoBaSS harmonizes the models capabilities across conversational and mathematical domains proving its efficacy and adaptability.
