---
layout: publication
title: Cos Enhancing Personalization And Mitigating Bias With Context Steering
authors: He Jerry Zhi-yang, Pandey Sashrika, Schrum Mariah L., Dragan Anca
conference: "Arxiv"
year: 2024
bibkey: he2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01768"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
When querying a large language model (LLM) the context i.e. personal demographic and cultural information specific to an end-user can significantly shape the response of the LLM. For example asking the model to explain Newtons second law with the context I am a toddler yields a different answer compared to the context I am a physics professor. Proper usage of the context enables the LLM to generate personalized responses whereas inappropriate contextual influence can lead to stereotypical and potentially harmful generations (e.g. associating female with housekeeper). In practice striking the right balance when leveraging context is a nuanced and challenging problem that is often situation-dependent. One common approach to address this challenge is to fine-tune LLMs on contextually appropriate responses. However this approach is expensive time-consuming and not controllable for end-users in different situations. In this work we propose Context Steering (CoS) - a simple training-free method that can be easily applied to autoregressive LLMs at inference time. By measuring the contextual influence in terms of token prediction likelihood and modulating it our method enables practitioners to determine the appropriate level of contextual influence based on their specific use case and end-user base. We showcase a variety of applications of CoS including amplifying the contextual influence to achieve better personalization and mitigating unwanted influence for reducing model bias. In addition we show that we can combine CoS with Bayesian Inference to quantify the extent of hate speech on the internet. We demonstrate the effectiveness of CoS on state-of-the-art LLMs and benchmarks.
