---
layout: publication
title: Ureader Universal Ocr45;free Visually45;situated Language Understanding With Multimodal Large Language Model
authors: Ye Jiabo, Hu Anwen, Xu Haiyang, Ye Qinghao, Yan Ming, Xu Guohai, Li Chenliang, Tian Junfeng, Qian Qi, Zhang Ji, Jin Qin, He Liang, Lin Xin Alex, Huang Fei
conference: "Arxiv"
year: 2023
bibkey: ye2023universal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05126"}
tags: ['Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Text is ubiquitous in our visual world conveying crucial information such as in documents websites and everyday photographs. In this work we propose UReader a first exploration of universal OCR45;free visually45;situated language understanding based on the Multimodal Large Language Model (MLLM). By leveraging the shallow text recognition ability of the MLLM we only finetuned 1.237; parameters and the training cost is much lower than previous work following domain45;specific pretraining and finetuning paradigms. Concretely UReader is jointly finetuned on a wide range of Visually45;situated Language Understanding tasks via a unified instruction format. To enhance the visual text and semantic understanding we further apply two auxiliary tasks with the same format namely text reading and key points generation tasks. We design a shape45;adaptive cropping module before the encoder45;decoder architecture of MLLM to leverage the frozen low45;resolution vision encoder for processing high45;resolution images. Without downstream finetuning our single model achieves state45;of45;the45;art ocr45;free performance in 8 out of 10 visually45;situated language understanding tasks across 5 domains documents tables charts natural images and webpage screenshots. Codes and instruction45;tuning datasets will be released.
