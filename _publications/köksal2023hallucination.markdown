---
layout: publication
title: Hallucination Augmented Recitations For Language Models
authors: Köksal Abdullatif, Aksitov Renat, Chang Chung-ching
conference: "Arxiv"
year: 2023
bibkey: köksal2023hallucination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07424"}
tags: ['Applications', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Attribution is a key concept in large language models (LLMs) as it enables control over information sources and enhances the factuality of LLMs. While existing approaches utilize open book question answering to improve attribution factual datasets may reward language models to recall facts that they already know from their pretraining data not attribution. In contrast counterfactual open book QA datasets would further improve attribution because the answer could only be grounded in the given text. We propose Hallucination Augmented Recitations (HAR) for creating counterfactual datasets by utilizing hallucination in LLMs to improve attribution. For open book QA as a case study we demonstrate that models finetuned with our counterfactual datasets improve text grounding leading to better open book QA performance with up to an 8.037; increase in F1 score. Our counterfactual dataset leads to significantly better performance than using humanannotated factual datasets even with 4x smaller datasets and 4x smaller models. We observe that improvements are consistent across various model sizes and datasets including multi45;hop biomedical and adversarial QA datasets.
