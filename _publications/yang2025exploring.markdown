---
layout: publication
title: 'Exploring Multimodal Challenges In Toxic Chinese Detection: Taxonomy, Benchmark, And Findings'
authors: Shujian Yang, Shiyao Cui, Chuanrui Hu, Haicheng Wang, Tianwei Zhang, Minlie Huang, Jialiang Lu, Han Qiu
conference: "Arxiv"
year: 2025
bibkey: yang2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24341"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting', 'In-Context Learning']
---
Detecting toxic content using language models is important but challenging. While large language models (LLMs) have demonstrated strong performance in understanding Chinese, recent studies show that simple character substitutions in toxic Chinese text can easily confuse the state-of-the-art (SOTA) LLMs. In this paper, we highlight the multimodal nature of Chinese language as a key challenge for deploying LLMs in toxic Chinese detection. First, we propose a taxonomy of 3 perturbation strategies and 8 specific approaches in toxic Chinese content. Then, we curate a dataset based on this taxonomy, and benchmark 9 SOTA LLMs (from both the US and China) to assess if they can detect perturbed toxic Chinese text. Additionally, we explore cost-effective enhancement solutions like in-context learning (ICL) and supervised fine-tuning (SFT). Our results reveal two important findings. (1) LLMs are less capable of detecting perturbed multimodal Chinese toxic contents. (2) ICL or SFT with a small number of perturbed examples may cause the LLMs "overcorrect'': misidentify many normal Chinese contents as toxic.
