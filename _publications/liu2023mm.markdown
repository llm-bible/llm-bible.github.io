---
layout: publication
title: Mm45;safetybench A Benchmark For Safety Evaluation Of Multimodal Large Language Models
authors: Liu Xin, Zhu Yichen, Gu Jindong, Lan Yunshi, Yang Chao, Qiao Yu
conference: "Arxiv"
year: 2023
bibkey: liu2023mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17600"}
  - {name: "Code", url: "https://github.com/isXinLiu/MM&#45;SafetyBench"}
tags: ['Has Code', 'Multimodal Models', 'Prompting', 'Responsible AI', 'Security', 'Tools']
---
The security concerns surrounding Large Language Models (LLMs) have been extensively explored yet the safety of Multimodal Large Language Models (MLLMs) remains understudied. In this paper we observe that Multimodal Large Language Models (MLLMs) can be easily compromised by query45;relevant images as if the text query itself were malicious. To address this we introduce MM45;SafetyBench a comprehensive framework designed for conducting safety45;critical evaluations of MLLMs against such image45;based manipulations. We have compiled a dataset comprising 13 scenarios resulting in a total of 5040 text45;image pairs. Our analysis across 12 state45;of45;the45;art models reveals that MLLMs are susceptible to breaches instigated by our approach even when the equipped LLMs have been safety45;aligned. In response we propose a straightforward yet effective prompting strategy to enhance the resilience of MLLMs against these types of attacks. Our work underscores the need for a concerted effort to strengthen and enhance the safety measures of open45;source MLLMs against potential malicious exploits. The resource is available at https://github.com/isXinLiu/MM&#45;SafetyBench
