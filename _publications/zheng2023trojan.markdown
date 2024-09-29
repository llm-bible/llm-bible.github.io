---
layout: publication
title: Trojfsp Trojan Insertion In Few45;shot Prompt Tuning
authors: Zheng Mengxin, Xue Jiaqi, Chen Xun, Wang Yanshan, Lou Qian, Jiang Lei
conference: "Arxiv"
year: 2023
bibkey: zheng2023trojan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10467"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security']
---
Prompt tuning is one of the most effective solutions to adapting a fixed pre45;trained language model (PLM) for various downstream tasks especially with only a few input samples. However the security issues e.g. Trojan attacks of prompt tuning on a few data samples are not well45;studied. Transferring established data poisoning attacks directly to few45;shot prompt tuning presents multiple challenges. One significant issue is the textit123;poisoned imbalance issue125; where non45;target class samples are added to the target class resulting in a greater number of target45;class samples compared to non45;target class. While this issue is not critical in regular tuning it significantly hampers the few45;shot prompt tuning making it difficult to simultaneously achieve a high attack success rate (ASR) and maintain clean data accuracy (CDA). Additionally few45;shot prompting is prone to overfitting in terms of both ASR and CDA. In this paper we introduce textit123;TrojFSP125; a method designed to address the challenges. To solve the poisoned imbalance issue we develop a textit123;Target45;Class Shrink (TC45;Shrink)125; technique which aims to equalize the number of poisoning samples. To combat overfitting we employ a textit123;Selective Token Poisoning125; technique to boost attack performance. Furthermore we introduce a textit123;Trojan45;Trigger Attention125; objective function to amplify the attention of the poisoned trojan prompt on triggers. Experiments show that our TrojFSP achieves an ASR of over 9937; while maintaining negligible decreases in CDA across various PLMs and datasets.
