---
layout: publication
title: Mplug45;owl Modularization Empowers Large Language Models With Multimodality
authors: Qinghao Ye, Haiyang Xu, Guohai Xu, Jiabo Ye, Ming Yan, Yiyang Zhou, Junyang Wang, Anwen Hu, Pengcheng Shi, Yaya Shi, Chenliang Li, Yuanhong Xu, Hehong Chen, Junfeng Tian, Qi Qian, Ji Zhang, Fei Huang, Jingren Zhou
conference: "Arxiv"
year: 2023
bibkey: ye2023mplug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2304.14178v3"}
  - {name: "Code", url: "https://github.com/X&#45;PLUG/mPLUG&#45;Owl"}
  - {name: "Code", url: "https://www.modelscope.cn/studios/damo/mPLUG&#45;Owl"}
tags: ['Fine Tuning', 'Has Code', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have demonstrated impressive zero45;shot abilities on a variety of open45;ended tasks while recent research has also explored the use of LLMs for multi45;modal generation. In this study we introduce mPLUG45;Owl a novel training paradigm that equips LLMs with multi45;modal abilities through modularized learning of foundation LLM a visual knowledge module and a visual abstractor module. This approach can support multiple modalities and facilitate diverse unimodal and multimodal abilities through modality collaboration. The training paradigm of mPLUG45;Owl involves a two45;stage method for aligning image and text which learns visual knowledge with the assistance of LLM while maintaining and even improving the generation abilities of LLM. In the first stage the visual knowledge module and abstractor module are trained with a frozen LLM module to align the image and text. In the second stage language45;only and multi45;modal supervised datasets are used to jointly fine45;tune a low45;rank adaption (LoRA) module on LLM and the abstractor module by freezing the visual knowledge module. We carefully build a visually45;related instruction evaluation set OwlEval. Experimental results show that our model outperforms existing multi45;modal models demonstrating mPLUG45;Owls impressive instruction and visual understanding ability multi45;turn conversation ability and knowledge reasoning ability. Besides we observe some unexpected and exciting abilities such as multi45;image correlation and scene text understanding which makes it possible to leverage it for harder real scenarios such as vision45;only document comprehension. Our code pre45;trained model instruction45;tuned models and evaluation set are available at https://github.com/X&#45;PLUG/mPLUG&#45;Owl. The online demo is available at https://www.modelscope.cn/studios/damo/mPLUG&#45;Owl.
