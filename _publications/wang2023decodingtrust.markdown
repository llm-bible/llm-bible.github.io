---
layout: publication
title: DecodingTrust A Comprehensive Assessment of Trustworthiness in GPT Models
authors: Wang Boxin, Chen Weixin, Pei Hengzhi, Xie Chulin, Kang Mintong, Zhang Chenhui, Xu Chejian, Xiong Zidi, Dutta Ritik, Schaeffer Rylan, Truong Sang T., Arora Simran, Mazeika Mantas, Hendrycks Dan, Lin Zinan, Cheng Yu, Koyejo Sanmi, Song Dawn, Li Bo
conference: "Arxiv"
year: 2023
bibkey: wang2023decodingtrust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.11698"}
tags: ['Applications', 'Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Security', 'Training Techniques', 'Transformer']
---
Generative Pre-trained Transformer (GPT) models have exhibited exciting progress in their capabilities capturing the interest of practitioners and the public alike. Yet while the literature on the trustworthiness of GPT models remains limited practitioners have proposed employing capable GPT models for sensitive applications such as healthcare and finance -- where mistakes can be costly. To this end this work proposes a comprehensive trustworthiness evaluation for large language models with a focus on GPT-4 and GPT-3.5 considering diverse perspectives -- including toxicity stereotype bias adversarial robustness out-of-distribution robustness robustness on adversarial demonstrations privacy machine ethics and fairness. Based on our evaluations we discover previously unpublished vulnerabilities to trustworthiness threats. For instance we find that GPT models can be easily misled to generate toxic and biased outputs and leak private information in both training data and conversation history. We also find that although GPT-4 is usually more trustworthy than GPT-3.5 on standard benchmarks GPT-4 is more vulnerable given jailbreaking system or user prompts potentially because GPT-4 follows (misleading) instructions more precisely. Our work illustrates a comprehensive trustworthiness evaluation of GPT models and sheds light on the trustworthiness gaps. Our benchmark is publicly available at https://decodingtrust.github.io/ ; our dataset can be previewed at https://huggingface.co/datasets/AI-Secure/DecodingTrust ; a concise version of this work is at https://openreview.net/pdf?id=kaHpo8OZw2 .
