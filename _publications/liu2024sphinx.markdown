---
layout: publication
title: SPHINX45;X Scaling Data And Parameters For A Family Of Multi45;modal Large Language Models
authors: Liu Dongyang, Zhang Renrui, Qiu Longtian, Huang Siyuan, Lin Weifeng, Zhao Shitian, Geng Shijie, Lin Ziyi, Jin Peng, Zhang Kaipeng, Shao Wenqi, Xu Chao, He Conghui, He Junjun, Shao Hao, Lu Pan, Li Hongsheng, Qiao Yu, Gao Peng
conference: "Arxiv"
year: 2024
bibkey: liu2024sphinx
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05935"}
  - {name: "Code", url: "https://github.com/Alpha&#45;VLLM/LLaMA2&#45;Accessory"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
We propose SPHINX45;X an extensive Multimodality Large Language Model (MLLM) series developed upon SPHINX. To improve the architecture and training efficiency we modify the SPHINX framework by removing redundant visual encoders bypassing fully45;padded sub45;images with skip tokens and simplifying multi45;stage training into a one45;stage all45;in45;one paradigm. To fully unleash the potential of MLLMs we assemble a comprehensive multi45;domain and multimodal dataset covering publicly available resources in language vision and vision45;language tasks. We further enrich this collection with our curated OCR intensive and Set45;of45;Mark datasets extending the diversity and generality. By training over different base LLMs including TinyLlama1.1B InternLM245;7B LLaMA245;13B and Mixtral8x7B we obtain a spectrum of MLLMs that vary in parameter size and multilingual capabilities. Comprehensive benchmarking reveals a strong correlation between the multi45;modal performance with the data and parameter scales. Code and models are released at https://github.com/Alpha&#45;VLLM/LLaMA2&#45;Accessory
