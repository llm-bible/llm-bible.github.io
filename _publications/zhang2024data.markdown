---
layout: publication
title: 'Data Watermarking For Sequential Recommender Systems'
authors: Sixiao Zhang, Cheng Long, Wei Yuan, Hongxu Chen, Hongzhi Yin
conference: "Arxiv"
year: 2024
bibkey: zhang2024data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.12989"}
tags: ['RecSys', 'Model Architecture', 'Attention Mechanism']
---
In the era of large foundation models, data has become a crucial component in building high-performance AI systems. As the demand for high-quality and large-scale data continues to rise, data copyright protection is attracting increasing attention. In this work, we explore the problem of data watermarking for sequential recommender systems, where a watermark is embedded into the target dataset and can be detected in models trained on that dataset. We focus on two settings: dataset watermarking, which protects the ownership of the entire dataset, and user watermarking, which safeguards the data of individual users. We present a method named Dataset Watermarking for Recommender Systems (DWRS) to address them. We define the watermark as a sequence of consecutive items inserted into normal users' interaction sequences. We define a Receptive Field (RF) to guide the inserting process to facilitate the memorization of the watermark. Extensive experiments on five representative sequential recommendation models and three benchmark datasets demonstrate the effectiveness of DWRS in protecting data copyright while preserving model utility.
