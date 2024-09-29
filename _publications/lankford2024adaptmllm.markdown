---
layout: publication
title: adaptMLLM Fine-Tuning Multilingual Language Models on Low-Resource Languages with Integrated LLM Playgrounds
authors: Lankford Séamus, Afli Haithem, Way Andy
conference: "Information"
year: 2024
bibkey: lankford2024adaptmllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02370"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
The advent of Multilingual Language Models (MLLMs) and Large Language Models has spawned innovation in many areas of natural language processing. Despite the exciting potential of this technology its impact on developing high-quality Machine Translation (MT) outputs for low-resource languages remains relatively under-explored. Furthermore an open-source application dedicated to both fine-tuning MLLMs and managing the complete MT workflow for low-resources languages remains unavailable. We aim to address these imbalances through the development of adaptMLLM which streamlines all processes involved in the fine-tuning of MLLMs for MT. This open-source application is tailored for developers translators and users who are engaged in MT. An intuitive interface allows for easy customisation of hyperparameters and the application offers a range of metrics for model evaluation and the capability to deploy models as a translation service directly within the application. As a multilingual tool we used adaptMLLM to fine-tune models for two low-resource language pairs English to Irish (ENGA) and English to Marathi (ENMR). Compared with baselines from the LoResMT2021 Shared Task the adaptMLLM system demonstrated significant improvements. In the EN→GA direction an improvement of 5.2 BLEU points was observed and an increase of 40.5 BLEU points was recorded in the GA→EN direction. Significant improvements in the translation performance of the ENMR pair were also observed notably in the MR→EN direction with an increase of 21.3 BLEU points. Finally a fine-grained human evaluation of the MLLM output on the EN→GA pair was conducted using the Multidimensional Quality Metrics and Scalar Quality Metrics error taxonomies. The application and models are freely available.
