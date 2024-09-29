---
layout: publication
title: 'Interpreting Key Mechanisms Of Factual Recall In Transformer-based Language Models'
authors: Lv Ang, Chen Yuhan, Zhang Kaiyi, Wang Yulong, Liu Lifeng, Wen Ji-rong, Xie Jian, Yan Rui
conference: "Arxiv"
year: 2024
bibkey: lv2024interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19521"}
tags: ['Attention Mechanism', 'Few Shot', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Transformer']
---
In this paper we delve into several mechanisms employed by Transformer-based language models (LLMs) for factual recall tasks. We outline a pipeline consisting of three major steps (1) Given a prompt The capital of France is task-specific attention heads extract the topic token such as France from the context and pass it to subsequent MLPs. (2) As attention heads outputs are aggregated with equal weight and added to the residual stream the subsequent MLP acts as an activation which either erases or amplifies the information originating from individual heads. As a result the topic token France stands out in the residual stream. (3) A deep MLP takes France and generates a component that redirects the residual stream towards the direction of the correct answer i.e. Paris. This procedure is akin to applying an implicit function such as get_capital(X) and the argument X is the topic token information passed by attention heads. To achieve the above quantitative and qualitative analysis for MLPs we proposed a novel analytic method aimed at decomposing the outputs of the MLP into components understandable by humans. Additionally we observed a universal anti-overconfidence mechanism in the final layer of models which suppresses correct predictions. We mitigate this suppression by leveraging our interpretation to improve factual recall confidence. The above interpretations are evaluated across diverse tasks spanning various domains of factual knowledge using various language models from the GPT-2 families 1.3B OPT up to 7B Llama-2 and in both zero- and few-shot setups.
