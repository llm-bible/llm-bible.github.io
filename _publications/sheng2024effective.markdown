---
layout: publication
title: 'Repeval: Effective Text Evaluation With LLM Representation'
authors: Shuqian Sheng, Yi Xu, Tianhang Zhang, Zanwei Shen, Luoyi Fu, Jiaxin Ding, Lei Zhou, Xiaoying Gan, Xinbing Wang, Chenghu Zhou
conference: "Arxiv"
year: 2024
bibkey: sheng2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19563"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
The era of Large Language Models (LLMs) raises new demands for automatic
evaluation metrics, which should be adaptable to various application scenarios
while maintaining low cost and effectiveness. Traditional metrics for automatic
text evaluation are often tailored to specific scenarios, while LLM-based
evaluation metrics are costly, requiring fine-tuning or rely heavily on the
generation capabilities of LLMs. Besides, previous LLM-based metrics ignore the
fact that, within the space of LLM representations, there exist direction
vectors that indicate the estimation of text quality. To this end, we introduce
RepEval, a metric that leverages the projection of LLM representations for
evaluation. Through simple prompt modifications, RepEval can easily transition
to various tasks, requiring only minimal sample pairs for direction vector
construction. Results on fourteen datasets across two evaluation tasks
demonstrate the high effectiveness of our method, which exhibits a higher
correlation with human judgments than previous methods, even in complex
evaluation scenarios involving pair-wise selection under nuanced aspects. Our
work underscores the richness of information regarding text quality embedded
within LLM representations, offering insights for the development of new
metrics.
