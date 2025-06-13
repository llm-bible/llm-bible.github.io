---
layout: publication
title: 'Generating Synthetic Documents For Cross-encoder Re-rankers: A Comparative Study Of Chatgpt And Human Experts'
authors: Arian Askari, Mohammad Aliannejadi, Evangelos Kanoulas, Suzan Verberne
conference: "Arxiv"
year: 2023
bibkey: askari2023generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.02320'}
tags: ['Training Techniques', 'Model Architecture', 'GPT']
---
We investigate the usefulness of generative Large Language Models (LLMs) in
generating training data for cross-encoder re-rankers in a novel direction:
generating synthetic documents instead of synthetic queries. We introduce a new
dataset, ChatGPT-RetrievalQA, and compare the effectiveness of models
fine-tuned on LLM-generated and human-generated data. Data generated with
generative LLMs can be used to augment training data, especially in domains
with smaller amounts of labeled data. We build ChatGPT-RetrievalQA based on an
existing dataset, human ChatGPT Comparison Corpus (HC3), consisting of public
question collections with human responses and answers from ChatGPT. We
fine-tune a range of cross-encoder re-rankers on either human-generated or
ChatGPT-generated data. Our evaluation on MS MARCO DEV, TREC DL'19, and TREC
DL'20 demonstrates that cross-encoder re-ranking models trained on ChatGPT
responses are statistically significantly more effective zero-shot re-rankers
than those trained on human responses. In a supervised setting, the
human-trained re-rankers outperform the LLM-trained re-rankers. Our novel
findings suggest that generative LLMs have high potential in generating
training data for neural retrieval models. Further work is needed to determine
the effect of factually wrong information in the generated responses and test
our findings' generalizability with open-source LLMs. We release our data,
code, and cross-encoders checkpoints for future work.
