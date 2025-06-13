---
layout: publication
title: 'GWQ: Gradient-aware Weight Quantization For Large Language Models'
authors: Yihua Shao, Yan Gu, Siyu Chen, Haiyang Liu, Zixian Zhu, Zijian Ling, Minxi Yan, Ziyang Yan, Chenyu Zhang, Michele Magno, Haotong Qin, Yan Wang, Jingcai Guo, Ling Shao, Hao Tang
conference: "Arxiv"
year: 2024
bibkey: shao2024gradient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00850"}
tags: ['Efficiency and Optimization', 'RAG', 'Language Modeling', 'Multimodal Models', 'Quantization']
---
Large language models (LLMs) show impressive performance in solving complex language tasks. However, its large number of parameters presents significant challenges for the deployment. So, compressing LLMs to low bits can enable to deploy on resource-constrained devices. To address this problem, we propose gradient-aware weight quantization (GWQ), the first quantization approach for low-bit weight quantization that leverages gradients to localize outliers, requiring only a minimal amount of calibration data for outlier detection. GWQ retains the top 1% outliers preferentially at FP16 precision, while the remaining non-outlier weights are stored in a low-bit. We widely evaluate GWQ on different task include language modeling, grounding detection, massive multitask language understanding and vision-language question and answering. Results show that models quantified by GWQ performs better than other quantization method. During quantization process, GWQ only need one calibration set to realize effective quant. Also, GWQ achieves 1.2x inference speedup in comparison to the original model and effectively reduces the inference memory.
