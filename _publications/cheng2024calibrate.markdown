---
layout: publication
title: 'Calibrate To Discriminate: Improve In-context Learning With Label-free Comparative Inference'
authors: Wei Cheng, Tianlu Wang, Yanmin Ji, Fan Yang, Keren Tan, Yiyu Zheng
conference: "Arxiv"
year: 2024
bibkey: cheng2024calibrate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02210'}
tags: ['Few-Shot', 'Prompting', 'In-Context Learning']
---
While in-context learning with large language models (LLMs) has shown
impressive performance, we have discovered a unique miscalibration behavior
where both correct and incorrect predictions are assigned the same level of
confidence. We refer to this phenomenon as indiscriminate miscalibration. We
found that traditional calibration metrics, such as Expected Calibrated Errors
(ECEs), are unable to capture this behavior effectively. To address this issue,
we propose new metrics to measure the severity of indiscriminate
miscalibration. Additionally, we develop a novel in-context comparative
inference method to alleviate miscalibrations and improve classification
performance. Through extensive experiments on five datasets, we demonstrate
that our proposed method can achieve more accurate and calibrated predictions
compared to regular zero-shot and few-shot prompting.
