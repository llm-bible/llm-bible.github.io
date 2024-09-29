---
layout: publication
title: Crossget Cross45;guided Ensemble Of Tokens For Accelerating Vision45;language Transformers
authors: Shi Dachuan, Tao Chaofan, Rao Anyi, Yang Zhendong, Yuan Chun, Wang Jiaqi
conference: "Arxiv"
year: 2023
bibkey: shi2023cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17455"}
  - {name: "Code", url: "https://github.com/sdc17/CrossGET"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Recent vision45;language models have achieved tremendous advances. However their computational costs are also escalating dramatically making model acceleration exceedingly critical. To pursue more efficient vision45;language Transformers this paper introduces Cross45;Guided Ensemble of Tokens (CrossGET) a general acceleration framework for vision45;language Transformers. This framework adaptively combines tokens in real45;time during inference significantly reducing computational costs while maintaining high performance. CrossGET features two primary innovations 1) Cross45;Guided Matching and Ensemble. CrossGET leverages cross45;modal guided token matching and ensemble to effectively utilize cross45;modal information achieving wider applicability across both modality45;independent models e.g. CLIP and modality45;dependent ones e.g. BLIP2. 2) Complete45;Graph Soft Matching. CrossGET introduces an algorithm for the token45;matching mechanism ensuring reliable matching results while facilitating parallelizability and high efficiency. Extensive experiments have been conducted on various vision45;language tasks such as image45;text retrieval visual reasoning image captioning and visual question answering. The performance on both classic multimodal architectures and emerging multimodal LLMs demonstrates the frameworks effectiveness and versatility. The code is available at https://github.com/sdc17/CrossGET.
