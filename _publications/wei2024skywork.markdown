---
layout: publication
title: Skywork45;moe A Deep Dive Into Training Techniques For Mixture45;of45;experts Language Models
authors: Wei Tianwen, Zhu Bo, Zhao Liang, Cheng Cheng, Li Biye, Lü Weiwei, Cheng Peng, Zhang Jianhao, Zhang Xiaoyu, Zeng Liang, Wang Xiaokun, Ma Yutuan, Hu Rui, Yan Shuicheng, Fang Han, Zhou Yahui
conference: "Arxiv"
year: 2024
bibkey: wei2024skywork
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06563"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
In this technical report we introduce the training methodologies implemented in the development of Skywork45;MoE a high45;performance mixture45;of45;experts (MoE) large language model (LLM) with 146 billion parameters and 16 experts. It is initialized from the pre45;existing dense checkpoints of our Skywork45;13B model. We explore the comparative effectiveness of upcycling versus training from scratch initializations. Our findings suggest that the choice between these two approaches should consider both the performance of the existing dense checkpoints and the MoE training budget. We highlight two innovative techniques gating logit normalization which improves expert diversification and adaptive auxiliary loss coefficients allowing for layer45;specific adjustment of auxiliary loss coefficients. Our experimental results validate the effectiveness of these methods. Leveraging these techniques and insights we trained our upcycled Skywork45;MoE on a condensed subset of our SkyPile corpus. The evaluation results demonstrate that our model delivers strong performance across a wide range of benchmarks.
