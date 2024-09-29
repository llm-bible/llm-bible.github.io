---
layout: publication
title: Tcptextual-based Class-aware Prompt Tuning For Visual-language Model
authors: Yao Hantao, Zhang Rui, Xu Changsheng
conference: "Arxiv"
year: 2023
bibkey: yao2023tcptextual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18231"}
  - {name: "Code", url: "https://github.com/htyao89/Textual-based_Class-aware_prompt_tuning/"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Prompt tuning represents a valuable technique for adapting pre-trained visual-language models (VLM) to various downstream tasks. Recent advancements in CoOp-based methods propose a set of learnable domain-shared or image-conditional textual tokens to facilitate the generation of task-specific textual classifiers. However those textual tokens have a limited generalization ability regarding unseen domains as they cannot dynamically adjust to the distribution of testing classes. To tackle this issue we present a novel Textual-based Class-aware Prompt tuning(TCP) that explicitly incorporates prior knowledge about classes to enhance their discriminability. The critical concept of TCP involves leveraging Textual Knowledge Embedding (TKE) to map the high generalizability of class-level textual knowledge into class-aware textual tokens. By seamlessly integrating these class-aware prompts into the Text Encoder a dynamic class-aware classifier is generated to enhance discriminability for unseen domains. During inference TKE dynamically generates class-aware prompts related to the unseen classes. Comprehensive evaluations demonstrate that TKE serves as a plug-and-play module effortlessly combinable with existing methods. Furthermore TCP consistently achieves superior performance while demanding less training time. Codehttps://github.com/htyao89/Textual-based_Class-aware_prompt_tuning/
