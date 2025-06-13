---
layout: publication
title: 'VQA4CIR: Boosting Composed Image Retrieval With Visual Question Answering'
authors: Chun-mei Feng, Yang Bai, Tao Luo, Zhen Li, Salman Khan, Wangmeng Zuo, Xinxing Xu, Rick Siow Mong Goh, Yong Liu
conference: "Arxiv"
year: 2023
bibkey: feng2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12273"}
tags: ['Fine-Tuning', 'Training Techniques', 'Applications', 'Pretraining Methods']
---
Albeit progress has been made in Composed Image Retrieval (CIR), we
empirically find that a certain percentage of failure retrieval results are not
consistent with their relative captions. To address this issue, this work
provides a Visual Question Answering (VQA) perspective to boost the performance
of CIR. The resulting VQA4CIR is a post-processing approach and can be directly
plugged into existing CIR methods. Given the top-C retrieved images by a CIR
method, VQA4CIR aims to decrease the adverse effect of the failure retrieval
results being inconsistent with the relative caption. To find the retrieved
images inconsistent with the relative caption, we resort to the "QA generation
to VQA" self-verification pipeline. For QA generation, we suggest fine-tuning
LLM (e.g., LLaMA) to generate several pairs of questions and answers from each
relative caption. We then fine-tune LVLM (e.g., LLaVA) to obtain the VQA model.
By feeding the retrieved image and question to the VQA model, one can find the
images inconsistent with relative caption when the answer by VQA is
inconsistent with the answer in the QA pair. Consequently, the CIR performance
can be boosted by modifying the ranks of inconsistently retrieved images.
Experimental results show that our proposed method outperforms state-of-the-art
CIR methods on the CIRR and Fashion-IQ datasets.
