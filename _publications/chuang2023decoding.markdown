---
layout: publication
title: "Dola: Decoding By Contrasting Layers Improves Factuality In Large Language Models"
authors: Chuang Yung-sung, Xie Yujia, Luo Hongyin, Kim Yoon, Glass James, He Pengcheng
conference: "Arxiv"
year: 2023
bibkey: chuang2023decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03883"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Despite their impressive capabilities large language models (LLMs) are prone to hallucinations i.e. generating content that deviates from facts seen during pretraining. We propose a simple decoding strategy for reducing hallucinations with pretrained LLMs that does not require conditioning on retrieved external knowledge nor additional fine-tuning. Our approach obtains the next-token distribution by contrasting the differences in logits obtained from projecting the later layers versus earlier layers to the vocabulary space exploiting the fact that factual knowledge in an LLMs has generally been shown to be localized to particular transformer layers. We find that this Decoding by Contrasting Layers (DoLa) approach is able to better surface factual knowledge and reduce the generation of incorrect facts. DoLa consistently improves the truthfulness across multiple choices tasks and open-ended generation tasks for example improving the performance of LLaMA family models on TruthfulQA by 12-1737; absolute points demonstrating its potential in making LLMs reliably generate truthful facts.
