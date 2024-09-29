---
layout: publication
title: IBD Alleviating Hallucinations In Large Vision45;language Models Via Image45;biased Decoding
authors: Lanyun Zhu, Deyi Ji, Tianrun Chen, Peng Xu, Jieping Ye, Jun Liu
conference: "Arxiv"
year: 2024
bibkey: zhu2024alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2402.18476v1"}
tags: ['Applications', 'Ethics And Bias', 'Tools', 'Training Techniques']
---
Despite achieving rapid developments and with widespread applications Large Vision45;Language Models (LVLMs) confront a serious challenge of being prone to generating hallucinations. An over45;reliance on linguistic priors has been identified as a key factor leading to these hallucinations. In this paper we propose to alleviate this problem by introducing a novel image45;biased decoding (IBD) technique. Our method derives the next45;token probability distribution by contrasting predictions from a conventional LVLM with those of an image45;biased LVLM thereby amplifying the correct information highly correlated with image content while mitigating the hallucinatory errors caused by excessive dependence on text. We further conduct a comprehensive statistical analysis to validate the reliability of our method and design an adaptive adjustment strategy to achieve robust and flexible handling under varying conditions. Experimental results across multiple evaluation metrics verify that our method despite not requiring additional training data and only with a minimal increase in model parameters can significantly reduce hallucinations in LVLMs and enhance the truthfulness of the generated response.
