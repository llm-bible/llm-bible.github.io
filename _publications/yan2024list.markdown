---
layout: publication
title: List Items One By One A New Data Source And Learning Paradigm For Multimodal Llms
authors: Yan An, Yang Zhengyuan, Wu Junda, Zhu Wanrong, Yang Jianwei, Li Linjie, Lin Kevin, Wang Jianfeng, Mcauley Julian, Gao Jianfeng, Wang Lijuan
conference: "Arxiv"
year: 2024
bibkey: yan2024list
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16375"}
  - {name: "Code", url: "https://github.com/zzxslp/SoM-LLaVA\"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Set-of-Mark (SoM) Prompting unleashes the visual grounding capability of GPT-4V by enabling the model to associate visual objects with tags inserted on the image. These tags marked with alphanumerics can be indexed via text tokens for easy reference. Despite the extraordinary performance from GPT-4V we observe that other Multimodal Large Language Models (MLLMs) struggle to understand these visual tags. To promote the learning of SoM prompting for open-source models we propose a new learning paradigm list items one by one which asks the model to enumerate and describe all visual tags placed on the image following the alphanumeric orders of tags. By integrating our curated dataset with other visual instruction tuning datasets we are able to equip existing MLLMs with the SoM prompting ability. Furthermore we evaluate our finetuned SoM models on five MLLM benchmarks. We find that this new dataset even in a relatively small size (10k-30k images with tags) significantly enhances visual reasoning capabilities and reduces hallucinations for MLLMs. Perhaps surprisingly these improvements persist even when the visual tags are omitted from input images during inference. This suggests the potential of list items one by one as a new paradigm for training MLLMs which strengthens the object-text alignment through the use of visual tags in the training stage. Finally we conduct analyses by probing trained models to understand the working mechanism of SoM. Our code and data are available at (url)https://github.com/zzxslp/SoM-LLaVA\}.
