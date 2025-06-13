---
layout: publication
title: 'Medsyn: Llm-based Synthetic Medical Text Generation Framework'
authors: Gleb Kumichev, Pavel Blinov, Yulia Kuzkina, Vasily Goncharov, Galina Zubkova, Nikolai Zenovkin, Aleksei Goncharov, Andrey Savchenko
conference: "Arxiv"
year: 2024
bibkey: kumichev2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02056"}
tags: ['Tools', 'GPT', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Generating synthetic text addresses the challenge of data availability in
privacy-sensitive domains such as healthcare. This study explores the
applicability of synthetic data in real-world medical settings. We introduce
MedSyn, a novel medical text generation framework that integrates large
language models with a Medical Knowledge Graph (MKG). We use MKG to sample
prior medical information for the prompt and generate synthetic clinical notes
with GPT-4 and fine-tuned LLaMA models. We assess the benefit of synthetic data
through application in the ICD code prediction task. Our research indicates
that synthetic data can increase the classification accuracy of vital and
challenging codes by up to 17.8% compared to settings without synthetic data.
Furthermore, to provide new data for further research in the healthcare domain,
we present the largest open-source synthetic dataset of clinical notes for the
Russian language, comprising over 41k samples covering 219 ICD-10 codes.
