---
layout: publication
title: Contrastive Triple Extraction with Generative Transformer
authors: Ye Hongbin, Zhang Ningyu, Deng Shumin, Chen Mosha, Tan Chuanqi, Huang Fei, Chen Huajun
conference: "Arxiv"
year: 2020
bibkey: ye2020contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.06207"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Triple extraction is an essential task in information extraction for natural language processing and knowledge graph construction. In this paper we revisit the end-to-end triple extraction task for sequence generation. Since generative triple extraction may struggle to capture long-term dependencies and generate unfaithful triples we introduce a novel model contrastive triple extraction with a generative transformer. Specifically we introduce a single shared transformer module for encoder-decoder-based generation. To generate faithful results we propose a novel triplet contrastive training object. Moreover we introduce two mechanisms to further improve model performance (i.e. batch-wise dynamic attention-masking and triple-wise calibration). Experimental results on three datasets (i.e. NYT WebNLG and MIE) show that our approach achieves better performance than that of baselines.
