---
layout: publication
title: Scheduled Sampling In Vision45;language Pretraining With Decoupled Encoder45;decoder Network
authors: Li Yehao, Pan Yingwei, Yao Ting, Chen Jingwen, Mei Tao
conference: "Arxiv"
year: 2021
bibkey: li2021scheduled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.11562"}
  - {name: "Code", url: "https://github.com/YehLi/TDEN&#125;"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Despite having impressive vision45;language (VL) pretraining with BERT45;based encoder for VL understanding the pretraining of a universal encoder45;decoder for both VL understanding and generation remains challenging. The difficulty originates from the inherently different peculiarities of the two disciplines e.g. VL understanding tasks capitalize on the unrestricted message passing across modalities while generation tasks only employ visual45;to45;textual message passing. In this paper we start with a two45;stream decoupled design of encoder45;decoder structure in which two decoupled cross45;modal encoder and decoder are involved to separately perform each type of proxy tasks for simultaneous VL understanding and generation pretraining. Moreover for VL pretraining the dominant way is to replace some input visual/word tokens with mask tokens and enforce the multi45;modal encoder/decoder to reconstruct the original tokens but no mask token is involved when fine45;tuning on downstream tasks. As an alternative we propose a primary scheduled sampling strategy that elegantly mitigates such discrepancy via pretraining encoder45;decoder in a two45;pass manner. Extensive experiments demonstrate the compelling generalizability of our pretrained encoder45;decoder by fine45;tuning on four VL understanding and generation downstream tasks. Source code is available at url123;https://github.com/YehLi/TDEN&#125;.
