---
layout: publication
title: 'Evaluating Hallucination In Text-to-image Diffusion Models With Scene-graph Based Question-answering Agent'
authors: Ziyuan Qin, Dongjie Cheng, Haoyu Wang, Huahui Yi, Yuting Shao, Zhiyuan Fan, Kang Li, Qicheng Lao
conference: "Arxiv"
year: 2024
bibkey: qin2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05722"}
tags: ['Merging', 'Agentic', 'Prompting', 'Tools']
---
Contemporary Text-to-Image (T2I) models frequently depend on qualitative
human evaluations to assess the consistency between synthesized images and the
text prompts. There is a demand for quantitative and automatic evaluation
tools, given that human evaluation lacks reproducibility. We believe that an
effective T2I evaluation metric should accomplish the following: detect
instances where the generated images do not align with the textual prompts, a
discrepancy we define as the `hallucination problem' in T2I tasks; record the
types and frequency of hallucination issues, aiding users in understanding the
causes of errors; and provide a comprehensive and intuitive scoring that close
to human standard. To achieve these objectives, we propose a method based on
large language models (LLMs) for conducting question-answering with an
extracted scene-graph and created a dataset with human-rated scores for
generated images. From the methodology perspective, we combine
knowledge-enhanced question-answering tasks with image evaluation tasks, making
the evaluation metrics more controllable and easier to interpret. For the
contribution on the dataset side, we generated 12,000 synthesized images based
on 1,000 composited prompts using three advanced T2I models. Subsequently, we
conduct human scoring on all synthesized images and prompt pairs to validate
the accuracy and effectiveness of our method as an evaluation metric. All
generated images and the human-labeled scores will be made publicly available
in the future to facilitate ongoing research on this crucial issue. Extensive
experiments show that our method aligns more closely with human scoring
patterns than other evaluation metrics.
