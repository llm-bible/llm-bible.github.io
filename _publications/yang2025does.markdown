---
layout: publication
title: 'Does Representation Intervention Really Identify Desired Concepts And Elicit Alignment?'
authors: Hongzheng Yang, Yongqiang Chen, Zeyu Qin, Tongliang Liu, Chaowei Xiao, Kun Zhang, Bo Han
conference: "Arxiv"
year: 2025
bibkey: yang2025does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18672"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Prompting', 'Applications']
---
Representation intervention aims to locate and modify the representations that encode the underlying concepts in Large Language Models (LLMs) to elicit the aligned and expected behaviors. Despite the empirical success, it has never been examined whether one could locate the faithful concepts for intervention. In this work, we explore the question in safety alignment. If the interventions are faithful, the intervened LLMs should erase the harmful concepts and be robust to both in-distribution adversarial prompts and the out-of-distribution (OOD) jailbreaks. While it is feasible to erase harmful concepts without degrading the benign functionalities of LLMs in linear settings, we show that it is infeasible in the general non-linear setting. To tackle the issue, we propose Concept Concentration (COCA). Instead of identifying the faithful locations to intervene, COCA refractors the training data with an explicit reasoning process, which firstly identifies the potential unsafe concepts and then decides the responses. Essentially, COCA simplifies the decision boundary between harmful and benign representations, enabling more effective linear erasure. Extensive experiments with multiple representation intervention methods and model architectures demonstrate that COCA significantly reduces both in-distribution and OOD jailbreak success rates, and meanwhile maintaining strong performance on regular tasks such as math and code generation.
