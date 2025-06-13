---
layout: publication
title: 'Unlabeled Data Improves Fine-grained Image Zero-shot Classification With Multimodal Llms'
authors: Yunqi Hong, Sohyun An, Andrew Bai, Neil Y. C. Lin, Cho-jui Hsieh
conference: "Arxiv"
year: 2025
bibkey: hong2025unlabeled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03195"}
  - {name: "Code", url: "https://github.com/yq-hong/AutoSEP"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Despite Multimodal Large Language Models (MLLMs) showing promising results on general zero-shot image classification tasks, fine-grained image classification remains challenging. It demands precise attention to subtle visual details to distinguish between visually similar subcategories--details that MLLMs may easily overlook without explicit guidance. To address this, we introduce AutoSEP, an iterative self-supervised prompt learning framework designed to enhance MLLM fine-grained classification capabilities in a fully unsupervised manner. Our core idea is to leverage unlabeled data to learn a description prompt that guides MLLMs in identifying crucial discriminative features within an image, and boosts classification accuracy. We developed an automatic self-enhancing prompt learning framework called AutoSEP to iteratively improve the description prompt using unlabeled data, based on instance-level classification scoring function. AutoSEP only requires black-box access to MLLMs, eliminating the need for any training or fine-tuning. We evaluate our approach on multiple fine-grained classification datasets. It consistently outperforms other unsupervised baselines, demonstrating the effectiveness of our self-supervised optimization framework. Notably, AutoSEP on average improves 13 percent over standard zero-shot classification and 5 percent over the best-performing baselines. Code is available at: https://github.com/yq-hong/AutoSEP
