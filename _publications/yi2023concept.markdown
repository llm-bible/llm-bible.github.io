---
layout: publication
title: Cones Concept Embedding Search For Parameter Efficient Tuning Large Vision Language Models
authors: Yi Huahui, Qin Ziyuan, Xu Wei, Guo Miaotian, Wang Kun, Zhang Shaoting, Li Kang, Lao Qicheng
conference: "Arxiv"
year: 2023
bibkey: yi2023concept
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18993"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large pre-trained vision-language models have shown great prominence in transferring pre-acquired knowledge to various domains and downstream tasks with appropriate prompting or tuning. Existing prevalent tuning methods can be generally categorized into three genres 1) prompt engineering by creating suitable prompt texts which is time-consuming and requires domain expertise; 2) or simply fine-tuning the whole model which is extremely inefficient; 3) prompt tuning through parameterized prompt embeddings with the text encoder. Nevertheless all methods rely on the text encoder for bridging the modality gap between vision and language. In this work we question the necessity of the cumbersome text encoder for a more lightweight and efficient tuning paradigm as well as more representative prompt embeddings closer to the image representations. To achieve this we propose a Concept Embedding Search (ConES) approach by optimizing prompt embeddings -- without the need of the text encoder -- to capture the concept of the image modality through a variety of task objectives. By dropping the text encoder we are able to significantly speed up the learning process (eg) from about an hour to just ten minutes in our experiments for personalized text-to-image generation without impairing the generation quality. Moreover our proposed approach is orthogonal to current existing tuning methods since the searched concept embeddings can be further utilized in the next stage of fine-tuning the pre-trained large models for boosting performance. Extensive experiments show that our approach can beat the prompt tuning and textual inversion methods in a variety of downstream tasks including objection detection instance segmentation and image generation. Our approach also shows better generalization capability for unseen concepts in specialized domains such as the medical domain.
