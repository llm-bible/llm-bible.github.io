---
layout: publication
title: Ensuring Safe And High45;quality Outputs A Guideline Library Approach For Language Models
authors: Luo Yi, Lin Zhenghao, Zhang Yuhao, Sun Jiashuo, Lin Chen, Xu Chengjin, Su Xiangdong, Shen Yelong, Guo Jian, Gong Yeyun
conference: "Arxiv"
year: 2024
bibkey: luo2024ensuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11838"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) exhibit impressive capabilities but also present risks such as biased content generation and privacy issues. One of the current alignment techniques includes principle45;driven integration but it faces challenges arising from the imprecision of manually crafted rules and inadequate risk perception in models without safety training. To address these we introduce Guide45;Align a two45;stage approach. Initially a safety45;trained model identifies potential risks and formulates specific guidelines for various inputs establishing a comprehensive library of guidelines and a model for input45;guidelines retrieval. Subsequently the retrieval model correlates new inputs with relevant guidelines which guide LLMs in response generation to ensure safe and high45;quality outputs thereby aligning with human values. An additional optional stage involves fine45;tuning a model with well45;aligned datasets generated through the process implemented in the second stage. Our method customizes guidelines to accommodate diverse inputs thereby enhancing the fine45;grainedness and comprehensiveness of the guideline library. Furthermore it incorporates safety expertise from a safety45;trained LLM through a lightweight retrieval model. We evaluate our approach on three benchmarks demonstrating significant improvements in LLM security and quality. Notably our fine45;tuned model Labrador even at 13 billion parameters outperforms GPT45;3.545;turbo and surpasses GPT45;4 in alignment capabilities.
