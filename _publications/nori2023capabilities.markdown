---
layout: publication
title: Capabilities of GPT-4 on Medical Challenge Problems
authors: Nori Harsha, King Nicholas, Mckinney Scott Mayer, Carignan Dean, Horvitz Eric
conference: "Arxiv"
year: 2023
bibkey: nori2023capabilities
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.13375"}
tags: ['GPT', 'Applications', 'Arxiv']
---
Large language models (LLMs) have demonstrated remarkable capabilities in natural language understanding and generation across various domains including medicine. We present a comprehensive evaluation of GPT-4 a state-of-the-art LLM on medical competency examinations and benchmark datasets. GPT-4 is a general-purpose model that is not specialized for medical problems through training or engineered to solve clinical tasks. Our analysis covers two sets of official practice materials for the USMLE a three-step examination program used to assess clinical competency and grant licensure in the United States. We also evaluate performance on the MultiMedQA suite of benchmark datasets. Beyond measuring model performance experiments were conducted to investigate the influence of test questions containing both text and images on model performance probe for memorization of content during training and study probability calibration which is of critical importance in high-stakes applications like medicine. Our results show that GPT-4 without any specialized prompt crafting exceeds the passing score on USMLE by over 20 points and outperforms earlier general-purpose models (GPT-3.5) as well as models specifically fine-tuned on medical knowledge (Med-PaLM a prompt-tuned version of Flan-PaLM 540B). In addition GPT-4 is significantly better calibrated than GPT-3.5 demonstrating a much-improved ability to predict the likelihood that its answers are correct. We also explore the behavior of the model qualitatively through a case study that shows the ability of GPT-4 to explain medical reasoning personalize explanations to students and interactively craft new counterfactual scenarios around a medical case. Implications of the findings are discussed for potential uses of GPT-4 in medical education assessment and clinical practice with appropriate attention to challenges of accuracy and safety.
