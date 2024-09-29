---
layout: publication
title: Chatgpt Based Data Augmentation For Improved Parameter45;efficient Debiasing Of Llms
authors: Han Pengrui, Kocielnik Rafal, Saravanan Adhithya, Jiang Roy, Sharir Or, Anandkumar Anima
conference: "Arxiv"
year: 2024
bibkey: han2024chatgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11764"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Large Language models (LLMs) while powerful exhibit harmful social biases. Debiasing is often challenging due to computational costs data constraints and potential degradation of multi45;task language capabilities. This work introduces a novel approach utilizing ChatGPT to generate synthetic training data aiming to enhance the debiasing of LLMs. We propose two strategies Targeted Prompting which provides effective debiasing for known biases but necessitates prior specification of bias in question; and General Prompting which while slightly less effective offers debiasing across various categories. We leverage resource45;efficient LLM debiasing using adapter tuning and compare the effectiveness of our synthetic data to existing debiasing datasets. Our results reveal that (1) ChatGPT can efficiently produce high45;quality training data for debiasing other LLMs; (2) data produced via our approach surpasses existing datasets in debiasing performance while also preserving internal knowledge of a pre45;trained LLM; and (3) synthetic data exhibits generalizability across categories effectively mitigating various biases including intersectional ones. These findings underscore the potential of synthetic data in advancing the fairness of LLMs with minimal retraining cost.
