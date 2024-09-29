---
layout: publication
title: Eyes Closed Safety On Protecting Multimodal Llms Via Image45;to45;text Transformation
authors: Gou Yunhao, Chen Kai, Liu Zhili, Hong Lanqing, Xu Hang, Li Zhenguo, Yeung Dit-yan, Kwok James T., Zhang Yu
conference: "Arxiv"
year: 2024
bibkey: gou2024eyes
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09572"}
tags: ['Fine Tuning', 'Multimodal Models', 'Responsible AI', 'Security', 'Training Techniques']
---
Multimodal large language models (MLLMs) have shown impressive reasoning abilities. However they are also more vulnerable to jailbreak attacks than their LLM predecessors. Although still capable of detecting the unsafe responses we observe that safety mechanisms of the pre45;aligned LLMs in MLLMs can be easily bypassed with the introduction of image features. To construct robust MLLMs we propose ECSO (Eyes Closed Safety On) a novel training45;free protecting approach that exploits the inherent safety awareness of MLLMs and generates safer responses via adaptively transforming unsafe images into texts to activate the intrinsic safety mechanism of pre45;aligned LLMs in MLLMs. Experiments on five state45;of45;the45;art (SoTA) MLLMs demonstrate that ECSO enhances model safety significantly (e.g. 37.637; improvement on the MM45;SafetyBench (SD+OCR) and 71.337; on VLSafe with LLaVA45;1.545;7B) while consistently maintaining utility results on common MLLM benchmarks. Furthermore we show that ECSO can be used as a data engine to generate supervised45;finetuning (SFT) data for MLLM alignment without extra human intervention.
