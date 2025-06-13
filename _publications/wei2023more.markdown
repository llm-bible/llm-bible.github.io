---
layout: publication
title: 'Skywork: A More Open Bilingual Foundation Model'
authors: Tianwen Wei, Liang Zhao, Lichang Zhang, Bo Zhu, Lijie Wang, Haihua Yang, Biye Li, Cheng Cheng, Weiwei Lü, Rui Hu, Chenxia Li, Liu Yang, Xilin Luo, Xuejie Wu, Lunan Liu, Wenjun Cheng, Peng Cheng, Jianhao Zhang, Xiaoyu Zhang, Lei Lin, Xiaokun Wang, Yutuan Ma, Chuanhai Dong, Yanqi Sun, Yifu Chen, Yongyi Peng, Xiaojuan Liang, Shuicheng Yan, Han Fang, Yahui Zhou
conference: "Arxiv"
year: 2023
bibkey: wei2023more
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.19341'}
tags: ['Pre-Training', 'Language Modeling', 'Training Techniques']
---
In this technical report, we present Skywork-13B, a family of large language
models (LLMs) trained on a corpus of over 3.2 trillion tokens drawn from both
English and Chinese texts. This bilingual foundation model is the most
extensively trained and openly published LLMs of comparable size to date. We
introduce a two-stage training methodology using a segmented corpus, targeting
general purpose training and then domain-specific enhancement training,
respectively. We show that our model not only excels on popular benchmarks, but
also achieves *state of the art* performance in Chinese language modeling
on diverse domains. Furthermore, we propose a novel leakage detection method,
demonstrating that test data contamination is a pressing issue warranting
further investigation by the LLM community. To spur future research, we release
Skywork-13B along with checkpoints obtained during intermediate stages of the
training process. We are also releasing part of our SkyPile corpus, a
collection of over 150 billion tokens of web text, which is the largest high
quality open Chinese pre-training corpus to date. We hope Skywork-13B and our
open corpus will serve as a valuable open-source resource to democratize access
to high-quality LLMs.
