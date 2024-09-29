---
layout: publication
title: Think Twice\: Measuring The Efficiency Of Eliminating Prediction Shortcuts Of Question Answering Models
authors: Mikula Lukáš, Štefánik Michal, Petrovič Marek, Sojka Petr
conference: "Arxiv"
year: 2023
bibkey: mikula2023think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.06841"}
tags: ['Applications', 'Efficiency And Optimization', 'Ethics And Bias', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
While the Large Language Models (LLMs) dominate a majority of language understanding tasks previous work shows that some of these results are supported by modelling spurious correlations of training datasets. Authors commonly assess model robustness by evaluating their models on out-of-distribution (OOD) datasets of the same task but these datasets might share the bias of the training dataset. We propose a simple method for measuring a scale of models reliance on any identified spurious feature and assess the robustness towards a large set of known and newly found prediction biases for various pre-trained models and debiasing methods in Question Answering (QA). We find that while existing debiasing methods can mitigate reliance on a chosen spurious feature the OOD performance gains of these methods can not be explained by mitigated reliance on biased features suggesting that biases are shared among different QA datasets. Finally we evidence this to be the case by measuring that the performance of models trained on different QA datasets relies comparably on the same bias features. We hope these results will motivate future work to refine the reports of LMs robustness to a level of adversarial samples addressing specific spurious features.
