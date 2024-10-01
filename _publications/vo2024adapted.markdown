---
layout: publication
title: 'Redwhale: An Adapted Korean LLM Through Efficient Continual Pretraining'
authors: Vo Anh-dung, Jung Minseong, Lee Wonbeen, Choi Daewoo
conference: "Arxiv"
year: 2024
bibkey: vo2024adapted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11294"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The field of Natural Language Processing (NLP) has seen significant advancements with the development of Large Language Models (LLMs). However, much of this research remains focused on English, often overlooking low-resource languages like Korean. This oversight presents challenges due to the unique non-alphabetic token structure of Korean and the substantial memory and computational demands required for LLM training, which frequently lead to memory constraints and out-of-memory errors. To address these issues, we present RedWhale, a model specifically tailored for Korean language processing. RedWhale is developed using an efficient continual pretraining approach that includes a comprehensive Korean corpus preprocessing pipeline, a specialized tokenizer, an optimized model initialization technique, and a multistage pretraining strategy. These innovations collectively reduce training time and computational costs while maintaining high levels of accuracy and comprehension. By leveraging cross-lingual transfer learning, which exploits shared linguistic similarities across languages, RedWhale builds on English models to enhance Korean language processing. Experimental results demonstrate that RedWhale outperforms other leading models on Korean NLP benchmarks, including the Korean Balanced Evaluation of Significant Tasks (KoBEST), showing superior understanding and generation of Korean text. Furthermore, RedWhale showed no signs of convergence even after pretraining on 9.7 billion tokens, indicating the potential for further improvements with additional training. This work represents a significant advancement in bridging the linguistic divide, particularly in enhancing NLP capabilities for the Korean language.
