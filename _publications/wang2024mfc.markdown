---
layout: publication
title: 'Mfc-bench: Benchmarking Multimodal Fact-checking With Large Vision-language Models'
authors: Shengkang Wang, Hongzhan Lin, Ziyang Luo, Zhen Ye, Guang Chen, Jing Ma
conference: "Arxiv"
year: 2024
bibkey: wang2024mfc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11288"}
  - {name: "Code", url: "https://github.com/wskbest/MFC-Bench,"}
tags: ['Multimodal Models', 'Model Architecture', 'Ethics and Bias', 'Has Code', 'Applications', 'Attention Mechanism']
---
Large vision-language models (LVLMs) have significantly improved multimodal
reasoning tasks, such as visual question answering and image captioning. These
models embed multimodal facts within their parameters, rather than relying on
external knowledge bases to store factual information explicitly. However, the
content discerned by LVLMs may deviate from factuality due to inherent bias or
incorrect inference. To address this issue, we introduce MFC-Bench, a rigorous
and comprehensive benchmark designed to evaluate the factual accuracy of LVLMs
across three stages of verdict prediction for MFC: Manipulation,
Out-of-Context, and Veracity Classification. Through our evaluation on
MFC-Bench, we benchmarked a dozen diverse and representative LVLMs, uncovering
that current models still fall short in multimodal fact-checking and
demonstrate insensitivity to various forms of manipulated content. We hope that
MFC-Bench could raise attention to the trustworthy AI potentially assisted by
LVLMs in the future. The MFC-Bench and accompanying resources are publicly
accessible at https://github.com/wskbest/MFC-Bench, contributing to ongoing
research in the multimodal fact-checking field.
