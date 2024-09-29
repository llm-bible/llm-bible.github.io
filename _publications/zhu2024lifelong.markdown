---
layout: publication
title: 'Lifelong Personalized Low-rank Adaptation Of Large Language Models For Recommendation'
authors: Zhu Jiachen, Lin Jianghao, Dai Xinyi, Chen Bo, Shan Rong, Zhu Jieming, Tang Ruiming, Yu Yong, Zhang Weinan
conference: "Arxiv"
year: 2024
bibkey: zhu2024lifelong
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03533"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We primarily focus on the field of large language models (LLMs) for recommendation which has been actively explored recently and poses a significant challenge in effectively enhancing recommender systems with logical reasoning abilities and open-world knowledge. Current mainstream efforts mainly center around injecting personalized information from recommendation models into LLMs by customizing input templates or aligning representations between semantic and recommendation spaces at the prediction layer. However they face three significant limitations (1) LoRA is mostly used as a core component in existing works but personalization is not well established in LoRA parameters as the LoRA matrix shared by every user may not cater to different users characteristics leading to suboptimal performance. (2) Although lifelong personalized behavior sequences are ideal for personalization their use raises effectiveness and efficiency issues since LLMs require escalating training and inference time to extend text lengths. (3) Existing approaches arent scalable for large datasets due to training efficiency constraints. Thus LLMs only see a small fraction of the datasets (e.g. less than 1037;) instead of the whole datasets limiting their exposure to the full training space. To address these problems we propose RecLoRA. This model incorporates a Personalized LoRA module that maintains independent LoRAs for different users and a Long-Short Modality Retriever that retrieves different history lengths for different modalities significantly improving performance while adding minimal time cost. Furthermore we design a Few2Many Learning Strategy using a conventional recommendation model as a lens to magnify small training spaces to full spaces. Extensive experiments on public datasets demonstrate the efficacy of our RecLoRA compared to existing baseline models.
