---
layout: publication
title: 'Why Context Matters In VQA And Reasoning: Semantic Interventions For VLM Input Modalities'
authors: Kenza Amara, Lukas Klein, Carsten Lüth, Paul Jäger, Hendrik Strobelt, Mennatallah El-assady
conference: "Arxiv"
year: 2024
bibkey: amara2024why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01690"}
tags: ['Model Architecture', 'Applications', 'Attention Mechanism', 'Reinforcement Learning']
---
The various limitations of Generative AI, such as hallucinations and model
failures, have made it crucial to understand the role of different modalities
in Visual Language Model (VLM) predictions. Our work investigates how the
integration of information from image and text modalities influences the
performance and behavior of VLMs in visual question answering (VQA) and
reasoning tasks. We measure this effect through answer accuracy, reasoning
quality, model uncertainty, and modality relevance. We study the interplay
between text and image modalities in different configurations where visual
content is essential for solving the VQA task. Our contributions include (1)
the Semantic Interventions (SI)-VQA dataset, (2) a benchmark study of various
VLM architectures under different modality configurations, and (3) the
Interactive Semantic Interventions (ISI) tool. The SI-VQA dataset serves as the
foundation for the benchmark, while the ISI tool provides an interface to test
and apply semantic interventions in image and text inputs, enabling more
fine-grained analysis. Our results show that complementary information between
modalities improves answer and reasoning quality, while contradictory
information harms model performance and confidence. Image text annotations have
minimal impact on accuracy and uncertainty, slightly increasing image
relevance. Attention analysis confirms the dominant role of image inputs over
text in VQA tasks. In this study, we evaluate state-of-the-art VLMs that allow
us to extract attention coefficients for each modality. A key finding is
PaliGemma's harmful overconfidence, which poses a higher risk of silent
failures compared to the LLaVA models. This work sets the foundation for
rigorous analysis of modality integration, supported by datasets specifically
designed for this purpose.
