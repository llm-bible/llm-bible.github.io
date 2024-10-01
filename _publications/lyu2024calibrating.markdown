---
layout: publication
title: 'Calibrating Large Language Models With Sample Consistency'
authors: Lyu Qing, Shridhar Kumar, Malaviya Chaitanya, Zhang Li, Elazar Yanai, Tandon Niket, Apidianaki Marianna, Sachan Mrinmaya, Callison-burch Chris
conference: "Arxiv"
year: 2024
bibkey: lyu2024calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13904"}
tags: ['Applications', 'Fine Tuning', 'Interpretability And Explainability', 'Scaling Laws']
---
Accurately gauging the confidence level of Large Language Models' (LLMs) predictions is pivotal for their reliable application. However, LLMs are often uncalibrated inherently and elude conventional calibration techniques due to their proprietary nature and massive scale. In this work, we explore the potential of deriving confidence from the distribution of multiple randomly sampled model generations, via three measures of consistency. We perform an extensive evaluation across various open and closed-source models on nine reasoning datasets. Results show that consistency-based calibration methods outperform existing post-hoc approaches. Meanwhile, we find that factors such as intermediate explanations, model scaling, and larger sample sizes enhance calibration, while instruction-tuning makes calibration more difficult. Moreover, confidence scores obtained from consistency have the potential to enhance model performance. Finally, we offer practical guidance on choosing suitable consistency metrics for calibration, tailored to the characteristics of various LMs.
