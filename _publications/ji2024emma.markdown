---
layout: publication
title: 'EMMA-500: Enhancing Massively Multilingual Adaptation Of Large Language Models'
authors: Shaoxiong Ji, Zihao Li, Indraneil Paul, Jaakko Paavola, Peiqin Lin, Pinzhen Chen, Dayyán O'brien, Hengyu Luo, Hinrich Schütze, Jörg Tiedemann, Barry Haddow
conference: "Arxiv"
year: 2024
bibkey: ji2024emma
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17892"}
tags: ['RAG', 'Training Techniques', 'Pre-Training', 'Reinforcement Learning']
---
In this work, we introduce EMMA-500, a large-scale multilingual language
model continue-trained on texts across 546 languages designed for enhanced
multilingual performance, focusing on improving language coverage for
low-resource languages. To facilitate continual pre-training, we compile the
MaLA corpus, a comprehensive multilingual dataset enriched with curated
datasets across diverse domains. Leveraging this corpus, we conduct extensive
continual pre-training of the Llama 2 7B model, resulting in EMMA-500, which
demonstrates robust performance across a wide collection of benchmarks,
including a comprehensive set of multilingual tasks. Our results highlight the
effectiveness of continual pre-training in expanding large language models'
language capacity, particularly for underrepresented languages, demonstrating
significant gains in cross-lingual transfer, task generalization, and language
adaptability. We release the MaLA corpus, EMMA-500 model weights, scripts, and
model generations.
