---
layout: publication
title: "Forcing Generative Models To Degenerate Ones: The Power Of Data Poisoning Attacks"
authors: Jiang Shuli, Kadhe Swanand Ravindra, Zhou Yi, Cai Ling, Baracaldo Nathalie
conference: "Arxiv"
year: 2023
bibkey: jiang2023forcing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04748"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Growing applications of large language models (LLMs) trained by a third party raise serious concerns on the security vulnerability of LLMs.It has been demonstrated that malicious actors can covertly exploit these vulnerabilities in LLMs through poisoning attacks aimed at generating undesirable outputs. While poisoning attacks have received significant attention in the image domain (e.g. object detection) and classification tasks their implications for generative models particularly in the realm of natural language generation (NLG) tasks remain poorly understood. To bridge this gap we perform a comprehensive exploration of various poisoning techniques to assess their effectiveness across a range of generative tasks. Furthermore we introduce a range of metrics designed to quantify the success and stealthiness of poisoning attacks specifically tailored to NLG tasks. Through extensive experiments on multiple NLG tasks LLMs and datasets we show that it is possible to successfully poison an LLM during the fine-tuning stage using as little as 137; of the total tuning data samples. Our paper presents the first systematic approach to comprehend poisoning attacks targeting NLG tasks considering a wide range of triggers and attack settings. We hope our findings will assist the AI security community in devising appropriate defenses against such threats.
