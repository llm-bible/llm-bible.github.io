---
layout: publication
title: "Explanation-aware Soft Ensemble Empowers Large Language Model In-context Learning"
authors: Yu Yue, Shen Jiaming, Liu Tianqi, Qin Zhen, Yan Jing Nathan, Liu Jialu, Zhang Chao, Bendersky Michael
conference: "Arxiv"
year: 2023
bibkey: yu2023explanation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07099"}
tags: ['Applications', 'In Context Learning', 'Interpretability And Explainability', 'Prompting', 'Tools']
---
Large language models (LLMs) have shown remarkable capabilities in various natural language understanding tasks. With only a few demonstration examples these LLMs can quickly adapt to target tasks without expensive gradient updates. Common strategies to boost such in-context learning ability are to ensemble multiple model decoded results and require the model to generate an explanation along with the prediction. However these models often treat different class predictions equally and neglect the potential discrepancy between the explanations and predictions. To fully unleash the power of explanations we propose EASE an Explanation-Aware Soft Ensemble framework to empower in-context learning with LLMs. We design two techniques explanation-guided ensemble and soft probability aggregation to mitigate the effect of unreliable explanations and improve the consistency between explanations and final predictions. Experiments on seven natural language understanding tasks and four varying-size LLMs demonstrate the effectiveness of our proposed framework.
