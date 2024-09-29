---
layout: publication
title: Tcptextual45;based Class45;aware Prompt Tuning For Visual45;language Model
authors: Yao Hantao, Zhang Rui, Xu Changsheng
conference: "Arxiv"
year: 2023
bibkey: yao2023class
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18231"}
  - {name: "Code", url: "https://github.com/htyao89/Textual&#45;based&#95;Class&#45;aware&#95;prompt&#95;tuning/"}
tags: ['Applications', 'Has Code', 'Prompting', 'RAG', 'Training Techniques']
---
Prompt tuning represents a valuable technique for adapting pre45;trained visual45;language models (VLM) to various downstream tasks. Recent advancements in CoOp45;based methods propose a set of learnable domain45;shared or image45;conditional textual tokens to facilitate the generation of task45;specific textual classifiers. However those textual tokens have a limited generalization ability regarding unseen domains as they cannot dynamically adjust to the distribution of testing classes. To tackle this issue we present a novel Textual45;based Class45;aware Prompt tuning(TCP) that explicitly incorporates prior knowledge about classes to enhance their discriminability. The critical concept of TCP involves leveraging Textual Knowledge Embedding (TKE) to map the high generalizability of class45;level textual knowledge into class45;aware textual tokens. By seamlessly integrating these class45;aware prompts into the Text Encoder a dynamic class45;aware classifier is generated to enhance discriminability for unseen domains. During inference TKE dynamically generates class45;aware prompts related to the unseen classes. Comprehensive evaluations demonstrate that TKE serves as a plug45;and45;play module effortlessly combinable with existing methods. Furthermore TCP consistently achieves superior performance while demanding less training time. Codehttps://github.com/htyao89/Textual&#45;based&#95;Class&#45;aware&#95;prompt&#95;tuning/
