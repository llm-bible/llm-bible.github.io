---
layout: publication
title: Transfer Learning For Sequence Generation From Single45;source To Multi45;source
authors: Huang Xuancheng, Xu Jingfang, Sun Maosong, Liu Yang
conference: "Arxiv"
year: 2021
bibkey: huang2021transfer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.14809"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Tools']
---
Multi45;source sequence generation (MSG) is an important kind of sequence generation tasks that takes multiple sources including automatic post45;editing multi45;source translation multi45;document summarization etc. As MSG tasks suffer from the data scarcity problem and recent pretrained models have been proven to be effective for low45;resource downstream tasks transferring pretrained sequence45;to45;sequence models to MSG tasks is essential. Although directly finetuning pretrained models on MSG tasks and concatenating multiple sources into a single long sequence is regarded as a simple method to transfer pretrained models to MSG tasks we conjecture that the direct finetuning method leads to catastrophic forgetting and solely relying on pretrained self45;attention layers to capture cross45;source information is not sufficient. Therefore we propose a two45;stage finetuning method to alleviate the pretrain45;finetune discrepancy and introduce a novel MSG model with a fine encoder to learn better representations in MSG tasks. Experiments show that our approach achieves new state45;of45;the45;art results on the WMT17 APE task and multi45;source translation task using the WMT14 test set. When adapted to document45;level translation our framework outperforms strong baselines significantly.
