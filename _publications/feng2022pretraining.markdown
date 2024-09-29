---
layout: publication
title: CERES Pretraining Of Graph45;conditioned Transformer For Semi45;structured Session Data
authors: Feng Rui, Luo Chen, Yin Qingyu, Yin Bing, Zhao Tuo, Zhang Chao
conference: "Arxiv"
year: 2022
bibkey: feng2022pretraining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.04303"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
User sessions empower many search and recommendation tasks on a daily basis. Such session data are semi45;structured which encode heterogeneous relations between queries and products and each item is described by the unstructured text. Despite recent advances in self45;supervised learning for text or graphs there lack of self45;supervised learning models that can effectively capture both intra45;item semantics and inter45;item interactions for semi45;structured sessions. To fill this gap we propose CERES a graph45;based transformer model for semi45;structured session data. CERES learns representations that capture both inter45; and intra45;item semantics with (1) a graph45;conditioned masked language pretraining task that jointly learns from item text and item45;item relations; and (2) a graph45;conditioned transformer architecture that propagates inter45;item contexts to item45;level representations. We pretrained CERES using ~468 million Amazon sessions and find that CERES outperforms strong pretraining baselines by up to 937; in three session search and entity linking tasks.
