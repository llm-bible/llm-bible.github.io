---
layout: publication
title: Evcap Retrieval45;augmented Image Captioning With External Visual45;name Memory For Open45;world Comprehension
authors: Li Jiaxuan, Vo Duc Minh, Sugimoto Akihiro, Nakayama Hideki
conference: "Arxiv"
year: 2023
bibkey: li2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.15879"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs)45;based image captioning has the capability of describing objects not explicitly observed in training data; yet novel objects occur frequently necessitating the requirement of sustaining up45;to45;date object knowledge for open45;world comprehension. Instead of relying on large amounts of data and/or scaling up network parameters we introduce a highly effective retrieval45;augmented image captioning method that prompts LLMs with object names retrieved from External Visual45;45;name memory (EVCap). We build ever45;changing object knowledge memory using objects visuals and names enabling us to (i) update the memory at a minimal cost and (ii) effortlessly augment LLMs with retrieved object names by utilizing a lightweight and fast45;to45;train model. Our model which was trained only on the COCO dataset can adapt to out45;of45;domain without requiring additional fine45;tuning or re45;training. Our experiments conducted on benchmarks and synthetic commonsense45;violating data show that EVCap with only 3.97M trainable parameters exhibits superior performance compared to other methods based on frozen pre45;trained LLMs. Its performance is also competitive to specialist SOTAs that require extensive training.
