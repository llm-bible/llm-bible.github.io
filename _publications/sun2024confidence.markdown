---
layout: publication
title: 'Confidence Estimation For Llm-based Dialogue State Tracking'
authors: Yi-jyun Sun, Suvodip Dey, Dilek Hakkani-tur, Gokhan Tur
conference: "Arxiv"
year: 2024
bibkey: sun2024confidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.09629"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Estimation of a model's confidence on its outputs is critical for
Conversational AI systems based on large language models (LLMs), especially for
reducing hallucination and preventing over-reliance. In this work, we provide
an exhaustive exploration of methods, including approaches proposed for open-
and closed-weight LLMs, aimed at quantifying and leveraging model uncertainty
to improve the reliability of LLM-generated responses, specifically focusing on
dialogue state tracking (DST) in task-oriented dialogue systems (TODS).
Regardless of the model type, well-calibrated confidence scores are essential
to handle uncertainties, thereby improving model performance. We evaluate four
methods for estimating confidence scores based on softmax, raw token scores,
verbalized confidences, and a combination of these methods, using the area
under the curve (AUC) metric to assess calibration, with higher AUC indicating
better calibration. We also enhance these with a self-probing mechanism,
proposed for closed models. Furthermore, we assess these methods using an
open-weight model fine-tuned for the task of DST, achieving superior joint goal
accuracy (JGA). Our findings also suggest that fine-tuning open-weight LLMs can
result in enhanced AUC performance, indicating better confidence score
calibration.
