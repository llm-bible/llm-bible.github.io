---
layout: publication
title: Medusa Simple LLM Inference Acceleration Framework With Multiple Decoding Heads
authors: Cai Tianle, Li Yuhong, Geng Zhengyang, Peng Hongwu, Lee Jason D., Chen Deming, Dao Tri
conference: "Arxiv"
year: 2024
bibkey: cai2024simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10774"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs) employ auto45;regressive decoding that requires sequential computation with each step reliant on the previous ones output. This creates a bottleneck as each step necessitates moving the full model parameters from High45;Bandwidth Memory (HBM) to the accelerators cache. While methods such as speculative decoding have been suggested to address this issue their implementation is impeded by the challenges associated with acquiring and maintaining a separate draft model. In this paper we present Medusa an efficient method that augments LLM inference by adding extra decoding heads to predict multiple subsequent tokens in parallel. Using a tree45;based attention mechanism Medusa constructs multiple candidate continuations and verifies them simultaneously in each decoding step. By leveraging parallel processing Medusa substantially reduces the number of decoding steps required. We present two levels of fine45;tuning procedures for Medusa to meet the needs of different use cases Medusa45;1 Medusa is directly fine45;tuned on top of a frozen backbone LLM enabling lossless inference acceleration. Medusa45;2 Medusa is fine45;tuned together with the backbone LLM enabling better prediction accuracy of Medusa heads and higher speedup but needing a special training recipe that preserves the backbone models capabilities. Moreover we propose several extensions that improve or expand the utility of Medusa including a self45;distillation to handle situations where no training data is available and a typical acceptance scheme to boost the acceptance rate while maintaining generation quality. We evaluate Medusa on models of various sizes and training procedures. Our experiments demonstrate that Medusa45;1 can achieve over 2.2x speedup without compromising generation quality while Medusa45;2 further improves the speedup to 2.345;3.6x.
