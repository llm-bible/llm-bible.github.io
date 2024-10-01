---
layout: publication
title: 'Cmm-math: A Chinese Multimodal Math Dataset To Evaluate And Enhance The Mathematics Reasoning Of Large Multimodal Models'
authors: Liu Wentao, Pan Qianjun, Zhang Yi, Liu Zhuo, Wu Ji, Zhou Jie, Zhou Aimin, Chen Qin, Jiang Bo, He Liang
conference: "Arxiv"
year: 2024
bibkey: liu2024cmm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02834"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) have obtained promising results in mathematical reasoning, which is a foundational skill for human intelligence. Most previous studies focus on improving and measuring the performance of LLMs based on textual math reasoning datasets (e.g., MATH, GSM8K). Recently, a few researchers have released English multimodal math datasets (e.g., MATHVISTA and MATH-V) to evaluate the effectiveness of large multimodal models (LMMs). In this paper, we release a Chinese multimodal math (CMM-Math) dataset, including benchmark and training parts, to evaluate and enhance the mathematical reasoning of LMMs. CMM-Math contains over 28,000 high-quality samples, featuring a variety of problem types (e.g., multiple-choice, fill-in-the-blank, and so on) with detailed solutions across 12 grade levels from elementary to high school in China. Specifically, the visual context may be present in the questions or opinions, which makes this dataset more challenging. Through comprehensive analysis, we discover that state-of-the-art LMMs on the CMM-Math dataset face challenges, emphasizing the necessity for further improvements in LMM development. We also propose a Multimodal Mathematical LMM (Math-LMM) to handle the problems with mixed input of multiple images and text segments. We train our model using three stages, including foundational pre-training, foundational fine-tuning, and mathematical fine-tuning. The extensive experiments indicate that our model effectively improves math reasoning performance by comparing it with the SOTA LMMs over three multimodal mathematical datasets.
