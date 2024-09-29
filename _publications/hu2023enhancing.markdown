---
layout: publication
title: Enhancing Answer Selection In Community Question Answering With Pre-trained And Large Language Models
authors: Hu Xinghang
conference: "Arxiv"
year: 2023
bibkey: hu2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17502"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Model Architecture', 'Prompting', 'Training Techniques', 'Transformer']
---
Community Question Answering (CQA) becomes increasingly prevalent in recent years. However there are a large number of answers which is difficult for users to select the relevant answers. Therefore answer selection is a very significant subtask of CQA. In this paper we first propose the Question-Answer cross attention networks (QAN) with pre-trained models for answer selection and utilize large language model (LLM) to perform answer selection with knowledge augmentation. Specifically we apply the BERT model as the encoder layer to do pre-training for question subjects question bodies and answers respectively then the cross attention mechanism selects the most relevant answer for different questions. Experiments show that the QAN model achieves state-of-the-art performance on two datasets SemEval2015 and SemEval2017. Moreover we use the LLM to generate external knowledge from questions and correct answers to achieve knowledge augmentation for the answer selection task by LLM while optimizing the prompt of LLM in different aspects. The results show that the introduction of external knowledge can improve the correct answer selection rate of LLM on datasets SemEval2015 and SemEval2017. Meanwhile LLM can also select the correct answer on more questions by optimized prompt.
