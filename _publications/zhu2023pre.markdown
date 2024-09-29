---
layout: publication
title: 3d45;vista Pre45;trained Transformer For 3D Vision And Text Alignment
authors: Zhu Ziyu, Ma Xiaojian, Chen Yixin, Deng Zhidong, Huang Siyuan, Li Qing
conference: "Arxiv"
year: 2023
bibkey: zhu2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04352"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
3D vision45;language grounding (3D45;VL) is an emerging field that aims to connect the 3D physical world with natural language which is crucial for achieving embodied intelligence. Current 3D45;VL models rely heavily on sophisticated modules auxiliary losses and optimization tricks which calls for a simple and unified model. In this paper we propose 3D45;VisTA a pre45;trained Transformer for 3D Vision and Text Alignment that can be easily adapted to various downstream tasks. 3D45;VisTA simply utilizes self45;attention layers for both single45;modal modeling and multi45;modal fusion without any sophisticated task45;specific design. To further enhance its performance on 3D45;VL tasks we construct ScanScribe the first large45;scale 3D scene45;text pairs dataset for 3D45;VL pre45;training. ScanScribe contains 2995 RGB45;D scans for 1185 unique indoor scenes originating from ScanNet and 3R45;Scan datasets along with paired 278K scene descriptions generated from existing 3D45;VL tasks templates and GPT45;3. 3D45;VisTA is pre45;trained on ScanScribe via masked language/object modeling and scene45;text matching. It achieves state45;of45;the45;art results on various 3D45;VL tasks ranging from visual grounding and dense captioning to question answering and situated reasoning. Moreover 3D45;VisTA demonstrates superior data efficiency obtaining strong performance even with limited annotations during downstream task fine45;tuning.
