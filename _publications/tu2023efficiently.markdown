---
layout: publication
title: 'Efficiently Aligned Cross-lingual Transfer Learning For Conversational Tasks Using Prompt-tuning'
authors: Lifu Tu, Jin Qu, Semih Yavuz, Shafiq Joty, Wenhao Liu, Caiming Xiong, Yingbo Zhou
conference: "Arxiv"
year: 2023
bibkey: tu2023efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01295"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
Cross-lingual transfer of language models trained on high-resource languages
like English has been widely studied for many NLP tasks, but focus on
conversational tasks has been rather limited. This is partly due to the high
cost of obtaining non-English conversational data, which results in limited
coverage. In this work, we introduce XSGD for cross-lingual alignment
pretraining, a parallel and large-scale multilingual conversation dataset that
we created by translating the English-only Schema-Guided Dialogue (SGD) dataset
(Rastogi et al., 2020) into 105 other languages. XSGD contains approximately
330k utterances per language. To facilitate aligned cross-lingual
representations, we develop an efficient prompt-tuning-based method for
learning alignment prompts. We also investigate two different classifiers:
NLI-based and vanilla classifiers, and test cross-lingual capability enabled by
the aligned prompts. We evaluate our model's cross-lingual generalization
capabilities on two conversation tasks: slot-filling and intent classification.
Our results demonstrate the strong and efficient modeling ability of NLI-based
classifiers and the large cross-lingual transfer improvements achieved by our
aligned prompts, particularly in few-shot settings. In addition, we highlight
the nice results of our approach compared to LLMs such as text-davinci-003 and
ChatGPT in both zero-shot and few-shot settings. While LLMs exhibit impressive
performance in English, their cross-lingual capabilities in other languages,
particularly low-resource languages, are limited.
