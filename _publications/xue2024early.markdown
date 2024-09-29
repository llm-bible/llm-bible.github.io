---
layout: publication
title: Openmoe An Early Effort On Open Mixture45;of45;experts Language Models
authors: Xue Fuzhao, Zheng Zian, Fu Yao, Ni Jinjie, Zheng Zangwei, Zhou Wangchunshu, You Yang
conference: "Arxiv"
year: 2024
bibkey: xue2024early
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01739"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
To help the open45;source community have a better understanding of Mixture45;of45;Experts (MoE) based large language models (LLMs) we train and release OpenMoE a series of fully open45;sourced and reproducible decoder45;only MoE LLMs ranging from 650M to 34B parameters and trained on up to over 1T tokens. Our investigation confirms that MoE45;based LLMs can offer a more favorable cost45;effectiveness trade45;off than dense LLMs highlighting the potential effectiveness for future LLM development. One more important contribution of this study is an in45;depth analysis of the routing mechanisms within our OpenMoE models leading to three significant findings Context45;Independent Specialization Early Routing Learning and Drop45;towards45;the45;End. We discovered that routing decisions in MoE models are predominantly based on token IDs with minimal context relevance. The token45;to45;expert assignments are determined early in the pre45;training phase and remain largely unchanged. This imperfect routing can result in performance degradation particularly in sequential tasks like multi45;turn conversations where tokens appearing later in a sequence are more likely to be dropped. Finally we rethink our design based on the above45;mentioned observations and analysis. To facilitate future MoE LLM development we propose potential strategies for mitigating the issues we found and further improving off45;the45;shelf MoE LLM designs.
