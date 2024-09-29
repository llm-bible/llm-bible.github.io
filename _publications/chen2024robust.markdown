---
layout: publication
title: Robust and Scalable Model Editing for Large Language Models
authors: Chen Yingfa, Zhang Zhengyan, Han Xu, Xiao Chaojun, Liu Zhiyuan, Chen Chen, Li Kuai, Yang Tao, Sun Maosong
conference: "Arxiv"
year: 2024
bibkey: chen2024robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17431"}
  - {name: "Code", url: "https://github.com/thunlp/EREN"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques']
---
Large language models (LLMs) can make predictions using parametric knowledge--knowledge encoded in the model weights--or contextual knowledge--knowledge presented in the context. In many scenarios a desirable behavior is that LLMs give precedence to contextual knowledge when it conflicts with the parametric knowledge and fall back to using their parametric knowledge when the context is irrelevant. This enables updating and correcting the models knowledge by in-context editing instead of retraining. Previous works have shown that LLMs are inclined to ignore contextual knowledge and fail to reliably fall back to parametric knowledge when presented with irrelevant context. In this work we discover that with proper prompting methods instruction-finetuned LLMs can be highly controllable by contextual knowledge and robust to irrelevant context. Utilizing this feature we propose EREN (Edit models by REading Notes) to improve the scalability and robustness of LLM editing. To better evaluate the robustness of model editors we collect a new dataset that contains irrelevant questions that are more challenging than the ones in existing datasets. Empirical results show that our method outperforms current state-of-the-art methods by a large margin. Unlike existing techniques it can integrate knowledge from multiple edits and correctly respond to syntactically similar but semantically unrelated inputs (and vice versa). The source code can be found at https://github.com/thunlp/EREN.
