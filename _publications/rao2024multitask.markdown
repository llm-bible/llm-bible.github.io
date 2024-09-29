---
layout: publication
title: RAVEN: Multitask Retrieval Augmented Vision-language Learning
authors: Rao Varun Nagaraj, Choudhary Siddharth, Deshpande Aditya, Satzoda Ravi Kumar, Appalaraju Srikar
conference: "Arxiv"
year: 2024
bibkey: rao2024multitask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19150"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The scaling of large language models to encode all the worlds knowledge in model parameters is unsustainable and has exacerbated resource barriers. Retrieval-Augmented Generation (RAG) presents a potential solution yet its application to vision-language models (VLMs) is under explored. Existing methods focus on models designed for single tasks. Furthermore theyre limited by the need for resource intensive pre training additional parameter requirements unaddressed modality prioritization and lack of clear benefit over non-retrieval baselines. This paper introduces RAVEN a multitask retrieval augmented VLM framework that enhances base VLMs through efficient task specific fine-tuning. By integrating retrieval augmented samples without the need for additional retrieval-specific parameters we show that the model acquires retrieval properties that are effective across multiple tasks. Our results and extensive ablations across retrieved modalities for the image captioning and VQA tasks indicate significant performance improvements compared to non retrieved baselines +1 CIDEr on MSCOCO +4 CIDEr on NoCaps and nearly a +337; accuracy on specific VQA question types. This underscores the efficacy of applying RAG approaches to VLMs marking a stride toward more efficient and accessible multimodal learning.
