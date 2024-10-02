---
layout: publication
title: 'Cmed-gpt: Prompt Tuning For Entity-aware Chinese Medical Dialogue Generation'
authors: Qu Zhijie, Li Juan, Ma Zerui, Li Jianqiang
conference: "Arxiv"
year: 2023
bibkey: qu2023cmed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.14539"}
tags: ['BERT', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Medical dialogue generation relies on natural language generation techniques to enable online medical consultations. Recently, the widespread adoption of large-scale models in the field of natural language processing has facilitated rapid advancements in this technology. Existing medical dialogue models are mostly based on BERT and pre-trained on English corpora, but there is a lack of high-performing models on the task of Chinese medical dialogue generation. To solve the above problem, this paper proposes CMed-GPT, which is the GPT pre-training language model based on Chinese medical domain text. The model is available in two versions, namely, base and large, with corresponding perplexity values of 8.64 and 8.01. Additionally, we incorporate lexical and entity embeddings into the dialogue text in a uniform manner to meet the requirements of downstream dialogue generation tasks. By applying both fine-tuning and p-tuning to CMed-GPT, we lowered the PPL from 8.44 to 7.35. This study not only confirms the exceptional performance of the CMed-GPT model in generating Chinese biomedical text but also highlights the advantages of p-tuning over traditional fine-tuning with prefix prompts. Furthermore, we validate the significance of incorporating external information in medical dialogue generation, which enhances the quality of dialogue generation.
